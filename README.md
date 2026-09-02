
L'objectif du projet est d'implémenter les algorithmes fondamentaux sur les automates finis déterministes, non déterministes, complets, non complets à l'aide de structures orientées objet.

* **Manipulation de base** :
  * Calcul de successeurs d'un état ou d'un ensemble d'états (`succElem`, `succ`).
  * Reconnaissance de mots par un automate (`accepte`).
  * Vérification du déterminisme (`estDeterministe`) et de la complétude (`estComplet`).
  * Complétion d'automate via état puits (`completeAutomate`).

* **Algorithmes avancés** :
  * Déterminisation d'automates (`determinisation`, `determinisation_etats`).
  * Opérations ensemblistes et rationnelles sur les langages :
    * Complémentaire (`complementaire`).
    * Intersection via produit cartésien (`intersection`).
    * Union (`union`).
    * Concaténation (`concatenation`) et Étoile de Kleene (`etoile`).
