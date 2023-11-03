# Checkpoint_algo_data_structure

## La somme des éléments distincts de deux tableaux
Soient deux tableaux :
    tab1 = {3, 1, 7, 9};
    tab2 = {2, 4, 1, 9, 3};

Les éléments distincts de ces tableaux sont : {7, 2, 4}

Pour trouver les éléments distincts nous allons comparer chaque éléments de tab1 aux éléments de tab2. S'il y'a aucune correspondance, on ajddition l'élément à la variable sum initialisé à 0.
On répéte le même processus pour les éléments de tab2
Au final, tous les éléments distincts sont additionnés et on se retrouve avec une somme sum = 13.

## Le produit scalaire
Soit un couple de vecteurs V1(X1,Y1) et V2(X2,Y2)
Leur produit scalaire est égale à ps = X1*X2 + Y1*Y2.

Pour écrire l'algorithme, nous allons d'abord créer une fonction ou procédure qui initialise le couple de vecteurs et un autre qui calcule le produit scalaire.

Ensuite, on utilisera ps pour déterminer si les vecteurs sont orthogonaux ou pas.