*Lo Codi* occitan
===

![Début du Codi occitan, ms. Paris, Sorbonne, 632, f. 1](https://nubis.univ-paris1.fr/iiif/3/BIS_00_00878_0009/51,118,1850,1020/max/0/default.jpg)
*Début du Codi occitan, ms. Paris, Sorbonne, 632, f. 1.*

Ce dépôt contient une édition critique de trois extraits de la somme au Code de Justinien d'après les témoins manuscrits Paris, Sorbonne, 632, Paris, BNF, NAF 4138 et 4504 réalisée en XML-TEI dans le cadre du master Technologies numériques appliquées à l'histoire de l'Ecole nationale des chartes.

Contenu du dépôt :
- `tei-codi-occ.xml` : encodage de l'édition ;
- `odd-codi-occ.xml` : ODD de l'édition ;
- `documentation-codi-occ.html` : export HTML du fichier `odd-codi-occ.xml` ;
- `schema-codi-occ.rng` : schéma de validation de l'édition ;
- `txt/` : contient les fichiers sources utilisés pour l'encodage au format texte brut :
    - `*_diplo.txt` : textes extraits de la ressource en ligne [Miroir des classiques](http://elec.enc.sorbonne.fr/miroir_des_classiques/xml/manuscrits_juridiques/codex_justinianus.xml#codi_occitan) ;
    - `*_interp.txt` : résultat de la normalisation des mêmes textes avant encodage (critères de normalisation explicités dans l'élément `normalization` du fichier `tei-codi-occ.xml`).