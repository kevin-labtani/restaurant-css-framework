# Projet site de restaurant en Bootstrap - **A Table**

![Aperçu du projet - capture d’écran](/project.png)

## Présentation du Projet

Projet créé le 07 Octobre 2019 dans le cadre de la formation Web Developer donnée par [BeCode](https://www.becode.org/), dans le but d'apprendre à utiliser Boostrap.

Le projet est réalisé sur base des [instructions données](https://github.com/becodeorg/CRL-Woods-2.15/blob/master/Projects/BootstrapProject/projet.md).

- [x] Codebase formated by [Prettier](https://prettier.io/)
- [x] Html validated by [W3C Markup Validation Service](https://validator.w3.org)

### **A Table**

Le Projet consite en un site Bootstrap de 5 pages, pésentant notre concept de restaurant nommé **A Table**.

_Nous sommes un petit restaurant où l'on peut bruncher avec ses amis ou bien sa famille.
Vous pouvez retrouver chez nous toutes sortes de pâtisseries, des bagels, des toasts, des céréales et même quelques petit plats. De quoi bien manger dans une ambiance familliale_.

## Contributeurs

- [**Denis Bourgeois**](https://github.com/Debourgeo)
- [**Kevin Labtani**](https://github.com/kevin-labtani)
- [**Gaby Pombo**](https://github.com/Gabypml)
- [**Christophe Ye Biname**](https://github.com/christophe-ye-biname)

## Commentaires

- **Kevin** (en charge de la _navbar_, du _footer_, de la page _contact_ et de ce _readme_):
  - J'ai appris à utiliser l'attribut `required` pour avoir une validation basique de mon formulaire par le navigateur web.
  - Suite à un audit **Google Lighthouse** de la page _contact.html_, j'ai rencontré des problèmes au niveau de l'accessibilité que j'ai résolu en rajoutant un attribut `aria-label` au bouton qui sert de `navbar-toggler` à Bootstrap, en rajoutant un `label` avec une classe custom `hidden` au `textarea` du formulaire, un "css trick" que j'ai trouvé sur [un sité dédié à l'accessibilité](https://webaim.org/techniques/css/invisiblecontent/), et en rajoutant un attribut `aria-hidden="true"` aux liens sociaux presents dans le footer.
  - De plus, suite à l'audit, j'ai rajouté un tag `meta description`.
  - J'ai aussi appris à générer et utiliser une _favicon_.

- **Christophe** (en charge de la gallerie):
  - J'ai appris un faire un carousel avec bootstrap et à y apporter certaines modifications.
  - Suite à un audit **Google Lighthouse** da la page _photos.html_ j'ai rencontré des problèmes au niveau de l'accessibilité mais que je n'ai su résoudre, ces problèmes étaient causés par des classes boostrap que je ne pouvais pas changé(ou ne voyais pas comment).
## Langages

Projet réalisé entièrement en HTML, Sass & jQuery

## Framework

[Bootstrap 4](https://getbootstrap.com/)

## Progression

Projet terminé le 11 Octobre 2019

## Remerciements

- [BeCode](https://www.becode.org/) pour la formation
- [Arnaud Duchemin](https://github.com/Cervant3s) pour le coaching
- La promotion **CRL-Woods-2.15** pour l'aide et le support
