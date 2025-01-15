## Configuration pour SSH :

### - Créer un vlan avec IP :

    #create vlan (nom du vlan ex: admin) tag (numéro vlan souhaité ex: 50)
    #configure (numéro du vlan admin donc 50 dans mon cas) ipaddress (ip) (masque)

### Génerer une clé SSH :

    #generate ssh rsa

### - Configuration d'un utilisateur SSH :

    #configure aaa user add (username) password (monmotdepasse)


### - Activation du SSH :

    #enable ssh

### - Configuration de l'authentification SSH local :

    #configure aaa authentication ssh local


### Vérification :

    #show aaa
    #show ssh


## Connexion au SSH :

### - Pré-requis :

Se brancher sur un port du vlan admin.


### - Deux solutions de connexion :

#### 1 - Putty :

Télécharger le logiciel Putty sur le site officiel : https://www.putty.org/

Une fois installé et lancé, une interface s'ouvre.

Il faut saisir :
  - IP vlan admin
  - séléctonner ssh

Puis cliquez sur "Open"


#### 2 - Terminal

    #ssh admin@(ip du vlan admin)
