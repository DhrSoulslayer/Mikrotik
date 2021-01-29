# Disclaimer
***Ik ben niet verantwoordelijk voor schade ontstaan door het gebruik van dit script.***
***Gebruik dit script alleen als je zelf volledig begrijpt wat het script doet.***

Markup :  - - - -


## WAN
De eerste interface van de Mikrotik(Ether1) wordt gezien als WAN Interface.
Deze zit in een bridge(BR_WAN) en op de bridge zitten de firewall regels.

## LAN
De ethernet interfaces tussen de eerste en de laatste zitten in een bridge voor het LAN.


## Management
De laatste interface wordt gezien als management/configuratie interface. 
Deze zit in de BR_MNGT waarop verschillende winbox services draaien en het beheer van de router gedaan kan worden.