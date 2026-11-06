# Education
L'IPS est une variable créée par la DEPP, service statistique du ministère de l'Éducation Nationale française.
Elle a été mise en place dès 2016, après sa création par Thierry Rocher.
Elle met en rapport les catégories socio-professionnelles des responsables de l'élèves, en supposant un poids différencié en fonction du lien qui unit l'enfant au parent. S'il s'agit de la mère, l'effet est plus positif sur la réussite scolaire que le père, à profession égale.
Ce qui suppose qu'aux catégories socio-professionnelles sont imputées des capitaux culturels, économiques et sociaux.
J'ai utilisé pour le code, la correspondance disponible sur le site de la DEPP mise à jour en 2022.

Les professions sont codées telle qu'elles sont indiquées dans le Tableau des correspondances CSP-IPS.


Attention : Les professions mal renseignées sont indiquées dans certaines bases par « 99 ». Ce qui doit être traité avant de faire tourner le code car ça rendra automatiquement un NA pour toute valeur non-correspondante a celle de la table.

Used for my codes of the IPS (a french government variables) on Rstudio : https://www.education.gouv.fr/depp/l-indice-de-position-sociale-ips-357755 

The current code use the nomenclature of 2022, re-written by Thierry Rocher.
