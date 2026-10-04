 Topologie du SOC Augmenté par IA

 Schéma de la topologie

https://lucid.app/lucidchart/e2cd9859-9092-415d-8590-cb7dafd18043/edit?invitationId=inv_7208a395-320e-45f5-a33e-694b5818463a&page=0_0#

Présentation

Cette topologie représente l'infrastructure réseau utilisée pour la réalisation du projet de SOC augmenté par l'intelligence artificielle.

Réseaux

- LAN1 : 192.168.10.1/24
- LAN2 : 192.168.20.1/24
- LAN3 : 192.168.30.1/24

Équipements

| Équipement |  Adresse IP     | Réseau | Rôle |
| Kali Attack | 192.168.10.10 | LAN1 | Machine d'attaque |
| pfSense | 192.168.10.1 | LAN1 | Pare-feu / routage |
| pfSense | 192.168.20.1 | LAN2 | Pare-feu / routage |
| Ubuntu Server | 192.168.20.10 | LAN2 | Serveur SOC |
| pfSense | 192.168.30.1 | LAN3 | Pare-feu / routage |
| Windows | 192.168.30.11 | LAN3 | Client |
| Ubuntu Client AIO | 192.168.30.20 | LAN3 | Client |

Objectif

Cette infrastructure permet de réaliser les tests de sécurité, la génération d'alertes, la collecte d'événements, la recherche d'IOC et le triage automatisé par IA.

Environnement

La topologie est réalisée avec GNS3 et utilise notamment :

- pfSense
- Kali Linux
- Ubuntu Server
- Windows
- Ubuntu Client AIO
- Switches
- NAT GNS3
