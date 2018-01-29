# Explications des concepts de Ruby on Rails (RoR) #

## Sommaire: ##
[1-La différence entre un site statique et un site dynamique:](#SD) X
[2-MVC: Model Vue Controller:](#MVC) X
[3-Les Routes:](#Routes) X
[4-Les Bases de Données:](#DB)
[5-GET/ POST:](#GP) X
[6-Le concept de migration:](#Mig) X
[7-Les relations entre les models des BDD:](#BDD)
8.[8-Les fonctions du CRUD:](#CRUD) X


## <a name="SD">1.La différence entre un site statique et un site dynamique.</a> ##
..* Un site Web statique est un site ou chacune des pages est créée en HTML. Un ordinateur qui se connecte au serveur, demande une page. Celle ci lui est directement servie (elle est stockée toute prête sur le serveur).
..* Par opposition, un site Web dynamique est un site Web dont les pages sont générées dynamiquement à la demande.
Le contenu est obtenu (par exemple) en combinant l’utilisation d’un langage de scripts ou de programmation et une base de données.


## <a name="MVC">2.MVC: Model Vue Controller.</a> ##
Le MVC est l'architecture sur laquelle se base Rails.
![alt text](https://image.slidesharecdn.com/rubyror-140609115622-phpapp01/95/ruby-on-rails-penetration-testing-5-638.jpg?cb=1402316148 "Architecture Rails")

En détaillants les actions on a:

  * L'utilisateur envoie, par le biais du Browser (navigateur), une requette à notre application.

  * Cette requette arrive dans le routeur et est distribué au bon Controleur. 

  * Le Controleur réagit aux actions de l'utilisateur, va aller chercher les données dans la base et va les mettre à disposition de la Vue.

  * Le controleur va interagir aussi avec les Models pour récupérer les informations dont il a besoin. Les Models assurent la gestion des données.

  * Le controleur envoie sa requette à la Vue et celle-ci génère une HTML complet.

  * Cet HTML est retourné au controleur qui le retourne à son tour au Browser de l'utilisateur.  
 

## <a name="Routes">3.Les Routes.</a> ##

Les routes interprètent les requettes URL et orientent vers les bonnes actions controlleurs.


## <a name="DB">4.Les Bases de Données.</a> ##

  *Ou BDD en abrégé, ou encore DB (anglais pour database).
  *C'est une sorte de tableur Excel géant.
  *Fichier ou ensemble de fichiers où l'on stocke des informations/données pour y accéder plus facilement et rapidement.
  *Le principe est d'avoir des clés/identifiants pour identifier le contenu et le lier à d'autres contenus de la BDD.

 Comme je le disais, schématiquement une BDD se présente comme un tableau :

  |Clés  |Valeurs    |Types |
  |------|-----------|------|
  |123456|"La valeur"|String|

## <a name="GP">5.GET/ POST</a> ##

 *GET = On demande de recevoir une info au serveur. Le GET se retrouvera directement comme argument dans l'URL.
    
  *POST = On envoie une info au serveur pour qu'il l'enregistre. Le POST sera défini dans le body de la page HTML.


## <a name="Mig">6.Le concept de migration.</a> ##
Tout simplement, la migration intervient lorsqu'on modifie la structure de la BDD.

Pour se faire, la commande utilisée dans Rails sera db:migrate. Auparavant, j'aurais modifié le fichier schema.rb dans le répertoire db et bien sûr sauvegardé ces modifications.

Pour en savoir plus (et parce que vous aimez les vidéos), je vous conseille de visionner l'excellent tutoriel de notre ami de Graphikart :

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/LBtCqTeJvfg/0.jpg)](http://www.youtube.com/watch?v=LBtCqTeJvfg)


## <a name="BDD">7.Les relations entre les models des BDD.</a> ##


## <a name="CRUD">8.Les fonctions du CRUD.</a> ##

  * Create, permet de créer un nouvel enregistrement.
  * Read, permet d'afficher un ou plusieurs enregistrements.
  * Update, permet de mettre à jour un enregistrement.
  * Update, permet de mettre à jour un enregistrement.

Pour approfondir vos connaissances un tour sur la page wikipedia de [Ruby on Rails](https://fr.wikipedia.org/wiki/Ruby_on_Rails) répondra certainement à certaines de vos questions