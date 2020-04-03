# DetoCS
DeToCs est un anti-cheat détectant un certain type de cheats.
 
Les cheats détectés sont généralement les plus lourds (ceux possédant Aimbot, ESP, etc...). 

Il ne détecte en aucun cas les materials hacks (pour cela, utilisez sv_pure). 
En effet, DeToCs n'a pas la prétention de pouvoir détecter tous les cheaters de votre serveur, 
mais peut néanmoins en attraper une partie. 

Le script est entièrement configurable pour adapter la détection à vos besoins (durée du ban, affichage d'informations, fréquence de vérification, ...). 

Le script ne peut normalement pas détecter un joueur sans qu'il n'ait un quelconque programme de cheat. Toutes les variables vérifiées ne peuvent être modifiées qu'en la présence d'un programme externe le permettant (sauf pour host_framerate). 

La détection est désactivée lorsque le serveur possède le sv_cheats à 1. 

Couplé avec sv_pure (efficace contre le material hack) et detox (efficace contre le speedhack et certains wallhacks), votre serveur sera débarrassé d'une grande partie des joueurs trichant.

A titre d'exemple, sur un serveur public de 16 ou 18 slots, 2 à 5 joueurs par jour environ sont détectés. 

Par [Team ToCs](http://www.team-tocs.com).

#### Installation
Décompresser l'archive, éditer le fichier de configuration (detocs.cfg) puis uploader le tout sur votre serveur. Il ne reste plus qu'à load le script (es_load detocs à mettre dans autoexec.cfg).  