# Bonjour et bienvenue sur ce Read me. #

# Concepts de base à connaitre en Ruby on Rails (RoR) #

![alt text](https://www.bacancytechnology.com/blog/wp-content/uploads/2014/08/rubyonrailswebapplicatondevelopment.png "Architecture Rails")

## Sommaire: ##
[1-La différence entre un site statique et un site dynamique.](#SD) 

[2-MVC: Model Vue Controller.](#MVC) 

[3-Les Routes.](#Routes) 

[4-Les Bases de Données.](#DB) 

[5-GET/ POST.](#GP) 

[6-Le concept de migration.](#Mig) 

[7-Les relations entre les models des BDD.](#BDD)

[8-Les fonctions du CRUD.](#CRUD) 


## <a name="SD">1.La différence entre un site statique et un site dynamique:</a> ##

 * Un site Web __statique__ est un site ou chacune des pages est créée en HTML. Un ordinateur qui se connecte au serveur, demande une page. Celle ci lui est directement servie (elle est stockée toute prête sur le serveur).
 
 * Par opposition, un site Web __dynamique__ est un site Web dont les pages sont générées dynamiquement à la demande.
 Le contenu est obtenu (par exemple) en combinant l’utilisation d’un langage de scripts ou de programmation et une base de données.


## <a name="MVC">2.MVC: Model Vue Controller.</a> ##
Le MVC est l'architecture sur laquelle se base Rails et peut être schématiquement représenté comme ceci:
![alt text](https://image.slidesharecdn.com/rubyror-140609115622-phpapp01/95/ruby-on-rails-penetration-testing-5-638.jpg?cb=1402316148 "Ruby on Rails")

En détaillants les actions on a:

  * L'utilisateur envoie, par le biais du Browser (navigateur), une requette à notre application.

  * Cette requette arrive dans le routeur et est distribué au bon Controleur. 

  * Le Controleur réagit aux actions de l'utilisateur, va aller chercher les données dans la base et va les mettre à disposition de la Vue.

  * Le controleur va interagir aussi avec les Models pour récupérer les informations dont il a besoin. Les Models assurent la gestion des données.

  * Le controleur envoie sa requette à la Vue et celle-ci génère une HTML complet.

  * Cet HTML est retourné au controleur qui le retourne à son tour au Browser de l'utilisateur.  
 

## <a name="Routes">3.Les Routes.</a> ##

Les routes interprètent les requettes URL et orientent vers les bonnes actions controlleurs.

Dans un projet Rails, on trouvera le fichier routes.rb dans le répertoire config.


## <a name="DB">4.Les Bases de Données.</a> ##

  * Ou BDD en abrégé, ou encore DB (anglais pour database).
  
  * C'est une sorte de tableur Excel géant.
  
  * Fichier ou ensemble de fichiers où l'on stocke des informations/données pour y accéder plus facilement et rapidement.
  
  * Le principe est d'avoir des clés/identifiants pour identifier le contenu et le lier à d'autres contenus de la BDD.

 Comme je le disais, schématiquement une BDD se présente comme un tableau :

  |Clés  |Valeurs    |Types |
  |------|-----------|------|
  |123456|"La valeur"|String|

  Voici une liste non exhaustive : SQLite, MySQL, PostgreSQL, Oracle, DB2, ...

## <a name="GP">5.GET/ POST</a> ##

 * __GET__ :On demande de recevoir une info au serveur. Le GET se retrouvera directement comme argument dans l'URL.
    
  * __POST__ : On envoie une info au serveur pour qu'il l'enregistre. Le POST sera défini dans le body de la page HTML.


## <a name="Mig">6.Le concept de migration.</a> ##

Les __migrations__ sont un moyen pratique de modifier votre base de données d'une manière structurée et organisée.

Pour se faire, la commande utilisée dans Rails sera db:migrate. Auparavant, j'aurais modifié le fichier schema.rb dans le répertoire db et bien sûr sauvegardé ces modifications.

Pour en savoir plus (et parce que vous aimez les vidéos), je vous conseille de visionner l'excellent tutoriel de notre ami de Graphikart :

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/LBtCqTeJvfg/0.jpg)](http://www.youtube.com/watch?v=LBtCqTeJvfg)


## <a name="BDD">7.Les relations entre les models des BDD.</a> ##

[Wikipedia](https://fr.wikipedia.org/wiki/Mod%C3%A8le_relationnel) définit le modèle relationnel comme "une manière de modéliser les relations existantes entre plusieurs informations, et de les ordonner entre elles. Cette modélisation qui repose sur des principes mathématiques mis en avant par E.F. Codd est souvent retranscrite physiquement (« implémentée ») dans une base de données."

Pour une bonne introduction aux bases de données relationnelles, la vidéo suivante est assez bien:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/4etRfqKF1XE/0.jpg)](http://www.youtube.com/watch?v=4etRfqKF1XE)


## <a name="CRUD">8.Les fonctions du CRUD.</a> ##

![alt text](https://www.google.fr/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=0ahUKEwi9rfmY_f3YAhVElxQKHSwTCDQQjRwIBw&url=http%3A%2F%2Fcoursework.vschool.io%2Fmongoose-crud%2F&psig=AOvVaw2lzqurk6PoC86kSVaHYA9j&ust=1517342971241986 "crud")

  * Create, permet de créer un nouvel enregistrement (PUT ou POST en HTTP).
  * Read, permet d'afficher un ou plusieurs enregistrements (GET en HTTP.
  * Update, permet de mettre à jour un enregistrement (PUT, POST ou PATH en HTTP).
  * Update, permet de mettre à jour un enregistrement (DELETE en HTTP).

Pour approfondir vos connaissances un tour sur la page wikipedia de [Ruby on Rails](https://fr.wikipedia.org/wiki/Ruby_on_Rails) répondra certainement à certaines de vos questions.

Merci pour votre lecture.

_Make by J.S._

