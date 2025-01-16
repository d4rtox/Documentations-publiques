## Configuration pour SSH :

### - Créer un vlan avec IP :

    #create vlan (nom du vlan ex: admin) tag (numéro vlan souhaité ex: 50)
    #configure (numéro du vlan admin donc 50 dans mon cas) ipaddress (ip) (masque)

### - Activation du SSH :

    #enable ssh

Une clé va se génerer automatiquement.

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
