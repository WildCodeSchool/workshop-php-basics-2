# Démarrage


Reprends le fichier `index.php` de ton dossier `basics` de [l'atelier précédent](https://wildcodeschool.github.io/workshop-php-basics-1/).  
Démarre un serveur HTTP sur ce dernier.
{: .alert-info }

## Boucle for


1.  Affiche les valeurs de 0 à 9 inclus via une boucle
2.  Affiche les valeurs de 10 à 0 inclus via une boucle
3.  Affiche les valeurs entre 10 à -10, avec des pas de 3

## Conditions

Reprenons votre variable `$firstPokemon = 'Bulbizarre';`

1.  Ecris une condition pour tester si `$firstPokemon` est égal à "Bulbizarre". Si c'est le cas, affiche "Bon choix".
2.  Sinon si `$firstPokemon` égal "Salamèche", affiche "Tu n'as aucune personnalité"
3.  Sinon affiche "Ah c'est donc \[FIRST\_POKEMON\_NAME\] ?" (remplacer par la valeur de ta variable)
4.  Modifie le choix de ton premier Pokemon via la variable `$firstPokemon` afin de tester toutes tes conditions

## Tableau indexé

Lors de ton aventure, tu vas devoir créer une équipe de Pokemon (jusqu'à 6 maximum). Essayons d'appliquer tout ça via la notion de tableaux indexés

Soit ton équipe de Pokemon composée de : `'Bulbizarre', 'Salamèche', 'Carapuce', 'Pikachu'`

1.  Créé un tableau `$pokemons` (indexé numériquement)
2.  Ajoute 'Mewto' dans ton équipe (et donc dans ton tableau)
3.  Affiche toute ton équipe en bouclant sur ton tableau

## Tableau associatif

Chaque Pokemon a un certain niveau selon l'expériene qu'il gagne dans le jeu. Créer un tableau associatif avec le nom en **clé** et le niveau en **valeur** :

*   **Bulbizarre** 15
*   **Salamèche** 7
*   **Carapuce** 3
*   **Pikachu** 45
*   **Mewto** 100

1.  Tu viens de battre ton premier champion d'arène et ton Bulbizarre a gagné un niveau. Change la valeur dans le tableau
2.  Lorsque certains Pokemon atteignent un certain niveau, ils évoluent. Bulbizarre évolue en Herbizarre au niveau 16. Afin de respecter cela, dans ton équipe, supprime le couple clé / valeur de Bulbizarre et remplace le par son évolution
3.  Classe ton équipe du niveau **le plus faible** au niveau **le plus élevé**, puis affiche les dans **une liste HTML**.
4.  Affiche uniquement les Pokemon ayant un niveau compris **entre 10 et 45** (non inclus)

## Tableaux multidimensionnels

Chaque Pokemon possède un type (ex : Pikachu est de type Electrik)

Soit les Pokemons suivants :

*   **Type Plante** : Bulbizarre, Mystherbe, Chetiflor
*   **Type Eau** : Carapuce, Stari, Magicarpe
*   **Type Feu** : Salamèche
*   **Type Sol** : Sabelette, Taupiqueur

Créé un tableau associatif, avec pour chaque élément de ce tableau :

*   En clé : Le type de Pokemon
*   En valeur : Un autre tableau contenant la liste des Pokemon concernée par le type en clé

1.  Ajoute "[Caninos](https://www.pokepedia.fr/Caninos)" dans ton tableau (le lien vous aidera à trouver son type et donc dans quel tableau l'ajouter)
2.  Ajoute ces Pokemon de type **Electrik** : Pikachu, Magneti, Voltorbe
3.  Affiche tous les Pokemon de type **Plante** en bouclant sur ton tableau.
4.  Affiche le nombre de Pokemon de type **Eau** qu'il y a dans ton tableau.

![meme pokemon](meme_girl.jpeg)