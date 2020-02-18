# siris
Outil de hiérarchisation de substances chimiques basé sur la méthode SIRIS

L'outil est présenté sous forme d'un fichier excel comportant 7 feuilles de calcul.
Les feuilles de calcul "Calcul1", "Calcul2", et "Calcul3" ne doivent pas être modifiées

# Fonctionnement
## Définition des classes
Dans la feuille "Principal", entrer le nombre de critère puis remplir la liste des ritères en indiquant leur nom, le nombre de modalité, et leur rang.
* Il ne peut y a avoir que deux critères par classes
* Il ne peut y avoir que 10 modalités par critère
* Il ne faut pas effectuer de saut dans la numérotation des classes

## Définition des modalités
Dans la feuille "Critères", remplir pour chaque critère les différentes modalités
* Soit en indiquant le texte correspondant à voter modalité
* soit sous la forme d'un intervalle 

## Ajout des données
Dans la feuille "Données", faites un copier/coller de vos données sans modifier l'ordre ou le contenu des titres des colonnes
Il n'est pas possible d'ajouter plus de 4000 lignes.

## Résultats
Dans la feuille "Résultats", vous trouverez les résultats de la hiérarchisation : le rang et le score obtenu par chaque substance.
