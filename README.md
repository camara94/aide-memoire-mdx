# Aide memoire en MDX
Dans ce t'article je vais essayer comprendre les bases du langage **MDX**

## Mythes et réalités sur le MDX
![mythe](images/mythe1.png)
![mythe](images/mythe2.png)
![mythe](images/mythe2-1.png)
![mythe](images/mythe3.png)
## Agenda
![agenda](images/agenda.png)

## MDX vs SQL
![mdxvssql](images/mdxvssql.png)
![mdxvssql](images/mdxvssql2.png)
## Problematique résolue par MDX
### Problematique 1 
![problematique](images/problematique.png)

#### Solution en MDX
![solution 1](images/solution1.png)
* il faut tout d"abord noter que les sont préceder par le mot clé **[Measure]** donc après on voit la mesure **[Reseller Sales Amount]**
* **ON 0** qui est équivalent de **ON ROW** c'est à dire l'affichage en ligne 
##### Requets 2
![solution 1](images/solution1.png)
##### Résultat de la requet 2
![solution 1](images/resultat2.png)

*  **ON 1** correspond à **ON COLUMN** c'est à dire l'afichage en colonne
*  **NON EMPTY** pour dire de ne récupérer que les cellules non vides
##### Cross Join
le cross join est introduit en MDX par l'operateur *
![cross join](images/crossjoin.png)
##### Résultat de Cross Join
![resultat 2](images/resultat2.png)

##### Trois axe ou encore l'axe de filtre
![filtre](images/axefiltre.png)
##### Resultat du filtre
![filtre](images/resultatfiltre.png)
##### Résumé
![resume](images/resumemdx.png)
### Problematique 2
![problematique 2](images/problematique2.png)
#### Solution en MDX
##### Sous cube requete(sous request)
![sous cube](images/sousrequetemdx.png)
c'est une sous requete ou sous cube qui comprend les France et Royaume Unit et l'intersection avec la categorie velo
##### Résultat sous cube
![resultat sous cube](images/resultatsouscube.png)

### Autres Requetes
#### Pourcentage
![percent](images/pourcentage.png)
#### Resultat en en paourcentage
![percent res](images/resulttatpercent.png)

### Les requetes géometriques
![reqgeome](images/reqgeometriques.png)
### Resultat Requete mesure géometrique
![req](images/resultatreqgeometriques.png)
#### Top 10 des clients
![top 10](images/top10.png)
#### Resultat top 10
![resultat top](images/resultattop10.png)
#### Sous Ctégories des parents 
![sous cube](images/souscategoriescontrib.png)
##### Requetes
![sous cube](images/souscategoriescontribreq.png)
##### Resultat 
![resultatsouscategoriescontribreq.png](images/resultatsouscategoriescontribreq.png)
#### La contribution d'une requete par rapport à son parent
![moi par rapport](images/moiparrapportamesparents.png)
#### Resultat
![moi par rapport](images/resulttatmoiparrapportamesparents.png)

## Niveau Expert
![niveau](images/niveauexpert.png)
### Exemple Niveau expert
![expert](images/exempleniveaubesoin.png)
### Affiché tous le montant sur toute l'année
![tmta](images/touslesmontantsurtousannees.png)
### Résultat
![tmta](images/resultattouslesmontantsurtousannees.png)

### Afficher les montants des années fiscales sur les mois fiscaux
![aa](images/anneefiscalsurmoisfiscal.png)
### Résultat
![aa](images/resultatanneefiscalsurmoisfiscal.png)
## Résumé
![resume](images/resumemdx2.png)
![re](images/resumegometrique.png)
![re](images/resumegometrique2.png)
![genialogie](images/genialogiemdx.png)
## Ressources
1. [Lien util](https://fjehl.wordpress.com/2012/04/16/le-mdx-cest-facile-enfin-presque/)
2. [les journées SQL Server](https://www.youtube.com/watch?v=C47Ysr4Tv8o&t=330s)