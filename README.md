# B2-Reseau-TP1

### Configuration de VirtualBox
* Il y a 254 adresses disponible dans un /24
* Il y a 2 adresses disponibles dans un /30
  * L'utilité est de pouvoir avoir uniquement 2 adresses IP disponibles en plus de l'adresse de réseau et l'adresse de broadcast

### Routes
* La première ligne correspond au réseau NAT
* la deuxième ligne correspond au réseau host-only en /24 
* La troisième ligne correspond au réseau host-only en /30

### Tables ARP
* La première ligne montre qu'on a communiqué avec l'adresse 10.1.1.1 dans le réseau en /24
* Le seconde ligne montre qu'on a communiqué avec l'adresse 10.1.2.1 dans le réseau en /30
---
* Cette nouvelle ligne montre bien qu'après le ping, l'adresse 10.1.2.1 a été enregistré dans la table ARP
