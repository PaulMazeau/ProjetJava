# Questions sur le "Figures Editor"

	Nom : Lissak Geller
	Prénom : Ariel
	Groupe : Prudhomme Lissak

## Objectif

L'objectif de ce petit questionnaire est de vous faire étudier le code du projet "Figures Editor" afin que vous puissiez mieux comprendre son fonctionnement.

## Travail à effectuer

Répondez aux questions ci-dessous directement dans ce fichier et déposez vos réponses sur le dépôt "ilo-questions-editor" avant le 04/04/2022 minuit.

### Pattern hunt

Recherchez dans le code du projet les différents Design patterns utilisés et listez les ci-dessous.


ColorFactory : Associe le nom des couleurs à leur valeur dans ColorFactory.java
IconFactory : Réalise un icon a partir d'une image dans IconFactory.java.

FlyWeight : Gère beaucoup d'éléments déjà utilisé en stockant leur état intrisèque (partie commune) et leur partie extrinsèque (partie propre à chaque élément) de manière séparée pour optimiser l'espace de stockage, construit dans Flyweight.java et utilisé dans StrokeFactory.java.

Prototype : Permet de créer une copie d'un objet de meme class, utilisé dans Memento.java et Figure.java.

Composite : Créer une succesion de test, à la manière d'un arbre, comme décrit dans le fichier CompositeFigureFilter.java, et utilisé dans le fichier Controller.java.

Memento : Sauvegarde l'été d'un objet à un moment donné, afin d'y accéder à n'importe quel moment sans passer par les détails de son implémentation, comme décrit dans Memento.java, et utilisé dans Drawing.java.

ObservableList : Permet de créer un abonnement (une communication automatique) pour informer les objets souhaités de différents changement sur l'objet regardé. A implémenter dans Drawing.java.

State : Permet a un objet de changer de comportement lorsque son etat interne change, utilisé dans HistoryManager.java.



> Vous pourrez avantageusement utiliser les fonctions de recherche d'Eclipse Menu Search -> File -> Containing text.

> Vous pouvez aussi rechercher les utilisations d'un symbole (un type ou une variable) dans tout le projet : Sélectionnez un symbole puis clic droit pour faire apparaître le menu contextuel -> References -> Project

> Lorsque vous pensez avoir identifié un Pattern précisez les éléments qui vous indiquent la présence de ce pattern et à quoi ou pourquoi il est utilisé. En d'autres termes, ne vous contentez pas de nommer un pattern sans préciser l'endroit où il est utilisé et pour quoi faire.

#### Liste des patterns utilisés dans le Figure Editor

* __Iterator__ : Inutile de le rechercher, il est partout dès que l'on a une collection comme dans `List<Figure> figures` dans la classe `figures.Drawing`, ou bien dans `Collection<FigureFilter<T>> filters` de la classe `filters.FigureFilters` par exemple.
* ...
