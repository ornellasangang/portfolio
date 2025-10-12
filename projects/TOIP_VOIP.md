# Implémentation de la Téléphonie sur IP (ToIP / VoIP) – Cisco Call Manager & Asterisk

## Objectif
Étudier et comparer deux architectures ToIP : une solution **Cisco Call Manager Express (CCME)** et une solution **Asterisk (Trixbox)**. Évaluer les protocoles SIP/RTP et la qualité de service (QoS) en conditions simulées.

## Travaux réalisés
- Configuration et déploiement d’un **Call Manager Cisco** sur un routeur passerelle.  
- Interconnexion d’un réseau de téléphones IP Cisco et de softphones (PhonerLite).  
- Mise en place d’un **serveur SIP Asterisk (Trixbox)** et configuration des clients.  
- Analyse des échanges SIP et des flux RTP/RTCP avec **Wireshark** (établissement d’appel, négociation codec).  
- Étude de la QoS : métriques de gigue, latence, perte de paquets selon différents codecs (G.711, G.729).  
- Simulation de congestion réseau et évaluation de l’impact sur la qualité audio.

## Environnement technique
- Cisco Call Manager Express (CCME)  
- Asterisk (Trixbox)  
- Téléphones IP Cisco, softphones (PhonerLite)  
- Routeurs Cisco, VMware pour VMs, Windows XP en VM (clients/test)  
- Outils : Wireshark, Putty, HyperTerminal, NetMeeting  
- Protocoles : SIP, RTP, RTCP ; codecs audio : G.711, G.729

## Compétences développées
- Administration et interconnexion d’équipements IP téléphoniques Cisco.  
- Configuration d’un serveur SIP open-source (Asterisk) et gestion des clients SIP.  
- Analyse réseau orientée multimédia (SIP/RTP) et diagnostic de la QoS.  
- Compréhension des contraintes temps réel sur réseaux IP et des stratégies d’optimisation (QoS, priorisation).

