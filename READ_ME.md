# Explications des concepts de Ruby on Rails (RoR) #

### Sommaire: ###
1.<a name="SD">La différence entre un site statique et un site dynamique.</a>
2.<a name="MVC">MVC: Model Vue Controller.</a>
3.<a name="Routes">Les Routes.</a>
4.<a name="DB">Les Bases de Données.</a>
5.<a name="GP">GET/ POST</a>
6.<a name="Mig">Le concept de migration.</a>
7.<a name="BDD">Les relations entre les models des BDD.</a>
8.<a name="CRUD">Les fonctions du CRUD.</a>

## [1-La différence entre un site statique et un site dynamique: ##](#SD)
..* Un site Web statique est un site ou chacune des pages est créée en HTML. Un ordinateur qui se connecte au serveur, demande une page. Celle ci lui est directement servie (elle est stockée toute prête sur le serveur).
..* Par opposition, un site Web dynamique est un site Web dont les pages sont générées dynamiquement à la demande.
Le contenu est obtenu (par exemple) en combinant l’utilisation d’un langage de scripts ou de programmation et une base de données.

## [2-MVC: Model Vue Controller:](#MVC)<a> ##

Le MVC est l'architecture sur laquelle se base Rails.
![alt text](https://image.slidesharecdn.com/rubyror-140609115622-phpapp01/95/ruby-on-rails-penetration-testing-5-638.jpg?cb=1402316148 "Architecture Rails")

En détaillants les actions on a:

..* L'utilisateur envoie, par le biais du Browser (navigateur), une requette à notre application.

..* Cette requette arrive dans le routeur et est distribué au bon Controleur. 

..* Le Controleur réagit aux actions de l'utilisateur, va aller chercher les données dans la base et va les mettre à disposition de la Vue.

..* Le controleur va interagir aussi avec les Models pour récupérer les informations dont il a besoin. Les Models assurent la gestion des données.

..* Le controleur envoie sa requette à la Vue et celle-ci génère une HTML complet.

..* Cet HTML est retourné au controleur qui le retourne à son tour au Browser de l'utilisateur.  

## [3-Les Routes:](#Routes) ##
Les routes interprètent les requettes URL et orientent vers les bonnes actions controlleurs.

## [4-Les Bases de Données:](#DB) ##

## [5-GET/ POST:](#GP) ##

## [6-Le concept de migration:](#Mig) ##

## [7-Les relations entre les models des BDD:](#BDD) ##

## [8-Les fonctions du CRUD:](#CRUD) ##

..* Create, permet de créer un nouvel enregistrement.
..* Read, permet d'afficher un ou plusieurs enregistrements.
..* Update, permet de mettre à jour un enregistrement.
..* Update, permet de mettre à jour un enregistrement.

Pour approfondir vos connaissances un tour sur la page wikipedia de [Ruby on Rails](https://fr.wikipedia.org/wiki/Ruby_on_Rails) répondra certainement à certaines de vos questions