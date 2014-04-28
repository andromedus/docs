# Team Andromedus

Alexis Hoshino, Eric Tian, HQ Pham-Nguyen, Kathleen Enverga

## What programming language(s) will you use?

+ PHP
+ HTML
+ JavaScript

## What framework(s), if any, will you use?

+ Bootstrap
+ Laravel

## What other libraries or dependencies will you use?

+ Composer, PHP Artisan
+ Flat UI
+ Vagrant
+ Facebook API

## Will you use different languages, frameworks, and/or libraries/dependencies for different parts of your application?

+ Yes
+ Front end will be primarily Bootstrap, FlatUI, HTML, CSS, and Laravel
+ Back end will be primarily PHP, MySQL, Facebook API

## What is your overall architecture (e.g., MVC)?

+ MVC: Different team members will take on a role each week, whether he or she is the model, view or controller.

## What data will you need to store?

+ Facebook user IDs
+ Memorials/memorial IDs
+ Collaborators
+  Users
+ Deceased facebook users’ data: photos, statuses, timeline information, login information

## What is your database design (or other data storage scheme)?

+ mySQL relational database

## Database
+ Video Table
+ Stories Table
+ Photos Table
+ Invitations Table
+ Statuses Table
+ Memorial Table
+ User_Memorial Join Table


## What are the other parts of your software? For example, for an MVC app: What models will you make? 

+ Content management system for the information that users share to timelines or memorials.
+ Mostly built based on existing models of entering, storing and displaying text and media.
+ Central database <-> Data preprocessor, content management system <-> Website front end

## Models
+ Invitation
+ Memorial
+  Photo
+ Profile
+ Story
+ User

## What attributes and methods will they have?

+ Our framework handles these attributes and methods automatically based on a CRUD design pattern, and creates the models automatically from our database tables.
+ Epilogue user attributes
+ User ID
+ Facebook user attributes
+ User ID
+ Deceased person’s attributes
+  Memorial ID
+ Memorial attributes
+ Memorial ID
+ Photos attributes
+ Memorial ID
+ Photo ID

## What controllers will you make?

+ Relational database tables, which will link the user to relevant information and features in the system.
+ Memorials, profiles, users, media content, and invitations will all have database tables to manage the information and relationships they represent.

## Controllers
+ BaseController
+ CollaboratorsController
+ Dashboard Controller
+ HomeController
+ LoginController
+ MemorialsController
+ PhotosController
+ StoriesController
+ StatusController
+ UsersController

## What methods will they have?

+ Each one of the controllers will have a very similar set of methods based on the CRUD design pattern.
++ Index
++ Create
++ Show
++ Store
++ Edit
++ Update
++ Destroy


## What views will you make?

### View
+ Videos
+ Photos
+ Status
+ Invitations
+ Collaborators
+ Story
+ Dashboard
+ Memorials
