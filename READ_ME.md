#Explications des concepts de Ruby on Rails (RoR)#

##1-La différence entre un site statique et un site dynamique:##
..*Un site Web statique est un site ou chacune des pages est créée en HTML. Un ordinateur qui se connecte au serveur, demande une page. Celle ci lui est directement servie (elle est stockée toute prête sur le serveur).
..*Par opposition, un site Web dynamique est un site Web dont les pages sont générées dynamiquement à la demande.
Le contenu est obtenu (par exemple) en combinant l’utilisation d’un langage de scripts ou de programmation et une base de données.

##2-MVC: Model Vue Controller:##

Le MVC est l'architecture sur laquelle se base Rails.
En détaillants les actions on a:

..*L'utilisateur envoie, par le biais du Browser (navigateur), une requette à notre application.

..*Cette requette arrive dans le routeur et est distribué au bon Controleur. 

..*Le Controleur réagit aux actions de l'utilisateur, va aller chercher les données dans la base et va les mettre à disposition de la Vue.

..*Le controleur va interagir aussi avec les Models pour récupérer les informations dont il a besoin. Les Models assurent la gestion des données.

..*Le controleur envoie sa requette à la Vue et celle-ci génère une HTML complet.

..*Cet HTML est retourné au controleur qui le retourne à son tour au Browser de l'utilisateur.  

##3-Les Routes:##
Les routes interprètent les requettes URL et orientent vers les bonnes actions controlleurs.

##4-Les Bases de Données:##

##5-GET/ POST:##

##6-Le concept de migration:##

##7-Les relations entre les models des BDD:##

##8-Les fonctions du CRUD:##

Pour approfondir vos connaissances un tour sur la page wikipedia de [Ruby on Rails](https://fr.wikipedia.org/wiki/Ruby_on_Rails) répondra certainement à certaines de vos questions