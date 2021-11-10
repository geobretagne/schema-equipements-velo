# Référentiel de données des équipements vélo

Spécification du modèle de données relatif aux équipements vélo

## Contexte

La Région Bretagne et Tourisme en Bretagne souhaitent développer l'offre de services le long des itinéraires vélo en Bretagne.</br>
En amont de la phase de recensement des équipements, un groupe de travail, animé par [GéoBretagne](https://geobretagne.fr), a co-construit un référentiel de données des équipements vélo. Après une première phase de concertation au niveau des acteurs bretons, plusieurs relecteurs nationaux ont validé le schéma proposé.</br>
Le document collaboratif du groupe de travail est visible [en ligne](https://docs.google.com/document/d/e/2PACX-1vTJOQw0eMIz8G03DL6oQ2PoRxbROSmbltUPFlGSAR-x6EGSVGnRD58G32OsHe8jNg/pub).</br>
Le modèle a été mis à jour pour prendre en compte le [schéma national du stationnement cyclable](https://schema.data.gouv.fr/etalab/schema-stationnement-cyclable/).</p>

### Format des fichiers

Le fichier doit être encodé en UTF-8 et utiliser le point-virgule comme séparateur de colonnes.</br>
Le nom du fichier comporte la date de création du jeu de données, la désignation du producteur et son code SIREN. Le tout sans espace ni accent et en minuscules, soit : equip_velo_producteur_siren_AAAAMMJJ.csv</br>
Exemples :</br>
equip_velo_sioca_802894816_20200611.csv</br>
equip_velo_regionbretagne_233500016_20200611.csv

## Fichiers d’exemples

Vous pouvez télécharger le fichier gabarit d’exemple au format :</br>
. [CSV](https://raw.githubusercontent.com/geobretagne/schema-equipements-velo/master/exemple-valide.csv)</br>
. [geopackage](https://raw.githubusercontent.com/geobretagne/schema-equipements-velo/master/exemple-valide.gpkg)

## Saisie des équipements

Vous pouvez télécharger le projet QGIS au [format QGZ](https://raw.githubusercontent.com/geobretagne/schema-equipements-velo/master/saisie-equipements-velo.qgz) pour réaliser  la saisie des équipements de votre territoire sur la base du fichier gabarit d’exemple au format.

En éditant la couche, un formulaire automatique permet d'alimenter la couche des équipements vélo en renseignant les champs.
Des tests sur [Qfield](https://qfield.org/) ont être réalisés avec succès pour effectuer la saisie terrain (mode connecté et déconnecté).

## Voir aussi

Pour poser une question, commenter, faire un retour d’usage ou contribuer à l’amélioration du modèle de données, vous pouvez :
- adresser un message à sig@bretagne.bzh
- ouvrir un ticket sur le [dépôt Github de GéoBretagne](https://github.com/geobretagne/schema-equipements-velo/issues)
