# funathon2023_sujet6

## A la recherche de l'alimentation perdue
![](images/Marcel_Proust.jpg "Marcel Proust")

## Objectif : Rechercher les aliments consommés dans l’œuvre de Proust

    Source : A la recherche du temps perdu

    Mise en pratique :
    - NLP
    - recherche d'entités nommées (NER)
    - la lecture de documents écrits par Marcel
    
## TODO list :
- Charger le fichier txt d'à la recherche du temps perdu
- Se familiariser avec la lib pyhton SPACY et produire des statistiques basiques du document (nombre de lettres, mots, lignes ...)
- Calcul des mots les plus fréquents (on pourra faire un wordcloud avec)
- Recherche d'entités nommées
    - utilisation de SPACY ou d'un modèle Huggingface spécialisé dans le NER en français
    - faire le "fine tuning" pour rajouter une catégorie d'entités FOOD
    - sortir la liste des références à des aliments du texte
      
## Data :
Les données sont disponibles sur minio, sur le sspcloud :


projet-funathon/2023/sujet6/data/Marcel Proust - A la recherche du temps perdu.txt

projet-funathon/2023/sujet6/data/ingredients.csv

## Bibliographie :
- Revue des deux mondes de juillet 2019 :
https://www.revuedesdeuxmondes.fr/proust-a-table-lire-a-la-recherche-du-temps-perdu-comme-un-livre-de-cuisine/

- L'article ci-dessus entier en pdf https://github.com/InseeFrLab/funathon2023_sujet6/blob/9ee042107aba35fbc78113476f1a79fa13924db9/doc/Revue%20de%202%20mondes%20-201907%20-%20proust.pdf

- Une méthode pour récupérer les ingrédients dans les recettes marmiton 
(attention ce script est en python 2 et ne marche certainement plus, mais le principe est là et on pourra utiliser cette liste des ingrédients)
https://dansmonlabo.com/2017/11/11/bataille-de-bouffe-decouvrez-les-ingredients-et-recettes-preferes-des-francais-1640/

