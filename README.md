# D-veloppement-d-un-syst-me-de-recommandation-de-livres-aux-clients

Développement d'un Système de recommandation de livres
Ce système de recommandation a pour but de prédire la note ou la préférence qu'un utilisateur attibuerait à un livre (Ouvrage) en considérant ses anciennes notes ou préferences des différents ouvrages. Ce type de système de recommandation est beaucoup plus utilisé par certaines compagnies dans le but d'améliorer considérablement la qualité de leur services mais aussi le chiffre d'affaire.

Dans le cadre de ce travail, nous utilisons 2 bases de données (Fichiers CSV, contenant respectivement les informations suivantes :

ratings.csv (taille 68,7 MO) dont la structure est :
user_id,book_id,rating

books.csv ( taille 3,13 MO) dont la structure est : book_id,goodreads_book_id,best_book_id,work_id,books_count,isbn,isbn13,authors,original_publication_year,original_title, title,language_code,average_rating,ratings_count,work_ratings_count,work_text_reviews_count,ratings_1,ratings_2,ratings_3, ratings_4,ratings_5,image_url,small_image_url

La travail est développé sous trois principaux points :

Chargement et analyse des données pertinentes pour l'étude
Développement de modèles
Recommandations
