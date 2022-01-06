# gundam
Projet E-Commerce GUNDAM

Description :

Application E-Commerce GUNDAM. Permettant de vendre des maquettes Gundam, de la peinture, des DVD/Bluray des films et séries, ainsi que tout autre goodies des univers Gundam.
Il s’agit de créer une application type E-Commerce classique, avec des listes de produits, une recherche, des filtres, un détail de produit, gestion de panier, paiement et de commande, etc… Avec également une gestion du compte utilisateur, et une gestion administrative pour les comptes et une gestion commerciale pour les ajouts de produits.

Technologique :

Le projet sera en WebService, donc les Front et le Back seront séparés en deux serveur :
Le BackEnd sera au choix : en Java, NodeJS, voir PHP. Un générateur de projet pourra être utilisé pour initialiser le back (exemple : JHipster pour Java ou Composer pour Symfony)
Le FrontEnd sera réalisé en ReactJS (voir en NextJS pour les intéressés). Les librairies minimales à utiliser seront : 
Formik et Yup pour la création et contrôle de formulaire
Axios pour les attaques d’API
Tailwind CSS en tant que framework de CSS
Redux Toolkit pour la gestion d’un store global à l’application
D’autres librairies pourront être rajouté au choix des développeurs (date-fns, moment, etc…)
La Base de Données sera dans un langage choisi (SQL (postgres), ou NoSQL (mongoDB))

Pour lancer le Back-end : npm start
Pour lancer le front-end : npm run dev
