## Administration Switch Extreme :

### - Création d'un VLAN :

	#Create vlan (nom du vlan) tag (num vlan)


### - Ajouter un descriptions à un port :

	#configure port 1 display-string "voir déscription"
 

### - Ajout d'une IP à un VLAN :

	#configure vlan (nom du vlan) ipaddress (adresse ip)


### - Aloué des vlan(s) à un port (TRUNK) :

	#configure vlan (nom du vlan) add ports (numéro de port) tagged
 

### - Aloué un vlan à un port (ACCESS) :

	#configure vlan (nom du vlan)  add ports (numéro du port) untagged


### - Activer l'INTER-VLAN :

	#enable ipforwarding VLAN (nom de vlan)


### - Sauvegarder la configuration :

	#save configuration


## Informations du switch :

### - Voir la version du switch :

	#show version
 

### - Voir les vlans :

 	#show vlan
  

### - Voir un vlan :

 	#show vlan (numéro de vlan)
  

### - Voir les ports associés d'un ou plusieurs vlan :

 	#show vlan ports (numéro de VLAN)

  
### - Voir les détails des vlans :

 	#show vlan details

  
### - Voir le details d'un vlan :

	#show vlan (numéro de vlan) detail
