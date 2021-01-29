# Disclaimer
***Ik ben niet verantwoordelijk voor schade ontstaan door het gebruik van dit script.***
***Gebruik dit script alleen als je zelf volledig begrijpt wat het script doet.***

- - - -


## WAN
De eerste interface wordt gezien als WAN Interface.
Deze zit in een bridge en op de bridge zitten de firewall regels.
Ook zit er op de brige een source nat met een masquarade regel.

## LAN
De ethernet interfaces tussen de eerste en de laatste zitten in een bridge voor het LAN.
Op de LAN Bridge draait een dhcp server voor LAN clients.

## Management
De laatste interface wordt gezien als management/configuratie interface. 
Op deze interface kan het beheer gedaan worden en zijn ook de verschillende winbox services beschikbaar.