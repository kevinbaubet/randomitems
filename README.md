# Documentation RandomItems

Ce script permet d'afficher aléatoirement des éléments.

## Initialisation

    $('#parent').randomItems([options]);


## Options

| Option      | Type     | Valeur par défaut | Description                                      |
|-------------|----------|-------------------|--------------------------------------------------|
| activeClass | string   | 'is-active'       | Classe sur l'élément enfant quand il est affiché |
| duration    | integer  | 3000              | Temps en ms entre chaque changement d'affichage  |
| loop        | boolean  | true              | L'affiche des éléments tourne en boucle          |
| shuffleLoop | boolean  | true              | Modifier l'ordre d'affichage à chaque boucle     |
| minItems    | integer  | 1                 | Nombre d'élément minimum à laisser afficher      |
| onChange    | function | undefined         | Callback à chaque changement d'état d'un élément |


## Méthodes

| Méthode       | Arguments      | Description                                                        |
|---------------|----------------|--------------------------------------------------------------------|
| destroy       | -              | Détruit le fonctionnement de RandomItems pour revenir à la normale |