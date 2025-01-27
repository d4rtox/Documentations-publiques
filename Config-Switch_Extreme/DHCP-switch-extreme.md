## Configuration DHCP :

### - Pré-requis :

    - Création d'un vlan
    - Ajout d'une IP à ce vlan
    - Ajout de ports à ce vlan


### - Activer le DHCP

    #enable dhcp ports ( range de port) vlan (nom de vlan)


### - Configuration du plages d'adresse IP :

    #configure vlan (nom du vlan) dhcp-address-range (adresse de début - adresse de fin)


### - Vérification du DHCP

    #show dhcp-server
