# Transfert de trafic UDP

## Objectif
Concevoir et implémenter un système de redirection et gestion de trafic UDP pour comprendre les contraintes du protocole sans connexion et gérer la fiabilité applicative.

## Travaux réalisés
- Développement d’un **serveur de redirection UDP** (forwarder) capable de router les messages entre clients.  
- Création d’un **client UDP** simple : envoi et réception de messages.  
- Mise en place d’un mécanisme pour **masquer/adresser** l’origine d’un client (rendre l’adresse inaccessible à l’autre).  
- Implémentation d’un acquittement applicatif : toutes les communications sont confirmées par un message de validation.  
- Gestion robuste des erreurs de connexion et prise en charge des différents cas d’envoi/timeout/retransmission.  
- Tests et capture des échanges réseau avec **Wireshark** pour validation.

## Environnement technique
- Langage : C (sockets UDP)  
- Plateforme : Linux (terminal)  
- Outils : Wireshark, Visual Studio Code, outils de débogage réseau

## Compétences développées
- Programmation socket bas niveau (UDP) en C.  
- Conception de protocoles applicatifs (acquittement, gestion d’erreurs).  
- Analyse de trafics réseau et debugging via Wireshark.  
- Notions de multithreading / gestion concurrente (si implémenté) et robustesse réseau.

