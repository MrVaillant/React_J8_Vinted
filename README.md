# Module : React

`Jour 8`

## Vinted

### URL.s

My React App : [![Netlify Status](https://api.netlify.com/api/v1/badges/442c11d2-e86f-4974-b2ac-c08e8b233569/deploy-status)]()

My BackEnd : [![Heroku](https://img.shields.io/badge/Heroku-%23430098.svg?style=flat&logo=heroku&logoColor=white)]()

Demo: [![Netlify](https://img.shields.io/badge/Netlify-%23000000.svg?style=flat&logo=netlify&logoColor=#00C7B7)](https://lereacteur-vinted.netlify.app/)

BackEnd de secours : [![Heroku](https://img.shields.io/badge/Heroku-%23430098.svg?style=flat&logo=heroku&logoColor=white)](https://lereacteur-vinted-api.herokuapp.com/offers)

> Méthode HTTP : `GET`

### RoadMap

- 1/ Nous allons commencer par afficher la liste des menus sur la page.
- 2/ Nous nous concentrerons donc uniquement sur la mise en place de la récupération des données de l'API et de la feuille de styles.

### Interactions

- Il sera possible pour l'utilisateur de choisir une annonce pour se rendre sur la page de celle-ci. Nous devrons mettre en place de la navigation grâce à React Router.
- Nous devrons mettre en page la barre de recherche dans le Header sans la travailler pour le moment sur la recherche en elle-même.

### Consigne.s // RoadMap

- [ ] Mettre en place React Router
- [ ] Créer les pages Home et Offer avec un lien permettant de passer d'une page à l'autre et ainsi tester la navigation
- [ ] Créer un composant Header dans lequel figurera le logo et trois boutons (s'inscrire, se connecter et vends tes articles ).
- [x] Aucune intéraction dans ce composant pour l'instant !

#### Route "Home"

- [ ] Réaliser l'intégration HTML (de la page Home dans un premier temps), sans trop de CSS
- [x] Ne pas essayer d'intégrer la forme qui permet de donner un effet "déchiré" à l'image du hero (BONUS)
- [ ] Créer les états
- [ ] Ajouter les interactions
- [ ] Réaliser le CSS

#### Route "Offer"

- [ ] Afficher le descriptif d'une annonce.

### Resultat attendu

<a href="https://lereacteur-react-deliveroo.netlify.com/" target="_blank">
<img align="center" height="490em" src="./src/img/Screenshot.png"/>
</a>

### Bonus

#### [ ] Pagination (Vinted - Home)

Permettre à l'utilisateur de parcourir les pages de résultats. L'API possède des paramètres skip et limit qui vous seront utiles pour récupérer seulement une partie des annonces de la base de données.

Exemples :

- Pour afficher la première page de résultats : https://lereacteur-vinted-api.herokuapp.com/offers?page=1&limit=8
- Pour afficher la deuxième page de résultats : https://lereacteur-vinted-api.herokuapp.com/offers?page=2&limit=8
- Pour afficher la troisième page de résultats : https://lereacteur-vinted-api.herokuapp.com/offers?page=3&limit=8

Note : Cette route permet aussi de récupérer le nombre d'annonces total dans la propriété count. Cette valeur aidera à calculer le nombre de pages maximum.

#### [ ] Effet "déchiré" du hero (Vinted - Home)

- Récupérez l'image sur https://www.vinted.fr/ pour l'intégrer au projet !

#### [ ] Carousel (Vinted - Offer)

Si les annonces possèdent plusieurs images, implémenter `react-multi-carousel` pour implémenter un carousel d'images.

[![LeReacteur](https://img.shields.io/badge/Make_with_Le_Reacteur.io-5C47D3?style=flat&logo=React&logoColor=white)](https://github.com/lereacteur)
# React_J8_Vinted
