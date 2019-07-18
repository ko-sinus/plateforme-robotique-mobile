# .step

Ce dossier recense les fichiers CAO .step (pour rappel, c'est le format "universel" pour les logiciels de CAO mecanique) de la plateforme robotique mobile.

Pour les transformer en fichiers urdf, il y a plusieurs methodes :

Pour Solidworks : http://wiki.ros.org/sw_urdf_exporter

Pour Fusion 360 (Autodesk) : https://github.com/syuntoku14/fusion2urdf

Pour les autres : en soi, un fichier urdf peut pointer vers un fichier .stl ou .dae. La difference entre ces deux fichiers est que le fichier .stl ne comprend que des donnees geometriques : s'il y a une couleur ou une texture a specifier, il faudra utiliser le format .dae.

Plus d'informations sur le format urdf ici : http://wiki.ros.org/fr/urdf/Tutorials
