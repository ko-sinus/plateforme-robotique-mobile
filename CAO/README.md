# .step

Ce dossier recense les fichiers CAO .step (pour rappel, c'est le format "universel" pour les logiciels de CAO mecanique) de la plateforme robotique mobile.

Pour les transformer en fichiers urdf, il y a plusieurs méthodes :

Pour Solidworks : http://wiki.ros.org/sw_urdf_exporter

Pour Fusion 360 (Autodesk) : https://github.com/syuntoku14/fusion2urdf

Pour les autres : il n'y a pas d'outils spécifiques à ce jour. Néanmoins, un fichier urdf peut pointer vers un fichier .stl ou .dae (collada). Il suffit donc d'exporter en l'un de ces formats les fichiers que vous souhaitez assigner à un objet "link", puis de les spécifier manuellement dans le fichier .urdf.
La différence entre .stl et .dae est que le fichier .stl ne comprend que des données géometriques : s'il y a une couleur ou une texture à spécifier, il faudra utiliser le format .dae.

Plus d'informations sur le format urdf ici : http://wiki.ros.org/fr/urdf/Tutorials
