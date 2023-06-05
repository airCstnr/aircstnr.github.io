# L'intégration continue en quatorze étapes

Alpes Craft 2023

Speaker: [Thierry de Pauw](https://thinkinglabs.io/index.html)

## Introduction

L'intégration continue est un ensemble de pratiques qui permettent de livrer rapidement un produit logiciel de qualité.

Nous allons présenter ici 14 pratiques essentielles à l'intégration continue.

## I. Conventions d'équipe

01. Tout placer sous gestionnaire de version
02. Accepter **en tant qu'équipe** de ne jamais casser le _Build_
03. Ne pas pousser sur un _Build_ cassé
04. Revert quand le _Build_ est cassé

## II. Code

05. Faire tous les changements en petits incréments
06. Commiter fréquemment
07. Commiter seulement quand les tests passent
08. Découpler le code
09. Utiliser le pattern **Expand-Contract**
10. Cacher les fonctionnalités qui ne sont pas terminées

## III. Construction

11. Automatiser le _Build_
12. Lancer le _Build_ localement
13. Avoir un grand nombre de tests automatisés de haute qualité
14. Avoir un _Build_ rapide

## Conclusion

Seulement 2 _outils_ sont nécessaires à toutes les pratiques de l'intégration continue :

- un gestionnaire de versions
- un script de construction qui prend moins de 10 minutes

## References

[The Practices That Make Continuous Integration](https://thinkinglabs.io/talks/2022/08/26/the-practices-that-make-continuous-integration.html)

[Slides](https://speakerdeck.com/tdpauw/the-practices-that-make-continuous-integration)
