## Configuration pour Telnet :

### - Créer un vlan avec IP :

    #create vlan (nom du vlan ex: admin) tag (numéro vlan souhaité ex: 50)
    #configure (numéro du vlan admin donc 50 dans mon cas) ipaddress (ip) (masque)


### - Activation du telnet :

    #enable telnet


### - Mot de passe telnet :

    #configure telnet password "monmotdepasse"


### - Vérifier la configuration :

    #show telnet

### - Ajout d'un utilisateur pour le telnet (optionnel) :

    #configure aaa user add (nom_utilisateur) password (mot_de_passe)

### Configurer l'authentification locale pour Telnet :

    #configure aaa authentication telnet local


## Connexion au telnet :

### - Pré-requis :

Se brancher sur un port du vlan admin.


### - Deux solutions de connexion :

#### 1 - Putty :

Télécharger le logiciel Putty sur le site officiel : [(https://www.putty.org/)]

Une fois installé et lancé, une interface s'ouvre.

Il faut saisir :
  - IP vlan admin
  - séléctonner "other" et options telnet

Puis cliquez sur "Open"


#### 2 - Terminal

    #telnet admin@(ip du vlan admin)
