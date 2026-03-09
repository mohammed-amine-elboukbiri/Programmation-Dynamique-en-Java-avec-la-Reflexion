#  Instanciation Dynamique des Classes et Injection de Dépendances en Java

## Objectif

L'objectif consiste à comprendre l'utilisation de la programmation dynamique en Java pour :

* Instancier des classes dynamiquement.
* Injecter des dépendances entre les classes.
* Invoquer des méthodes via la réflexion (*Reflection*).

Cette approche permet de charger dynamiquement des classes et de configurer une application sans dépendre d'une configuration statique dans le code source.

---

## Principe
 Nous utilisons la **réflexion en Java** pour :

1. Charger dynamiquement une classe à l’aide de `Class.forName()`.
2. Créer une instance de cette classe avec `newInstance()` ou `getConstructor().newInstance()`.
3. Injecter une dépendance entre deux classes.
4. Invoquer une méthode dynamiquement avec `Method.invoke()`.

Cette technique est utilisée dans plusieurs frameworks modernes comme **Spring** pour réaliser l’injection de dépendances.

---

## Affichage




---

