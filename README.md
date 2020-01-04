#   Setting up the server documentation

linux Os ->  Centos 7.5 , WHM/Cpnanel  server,  Cloud Linux security enable
php 5.6 , 7.1, 7.2
mysql  5.6 ,5.7
apache httpd 2.4
Proper Host Procedures
Android : https://play.google.com/apps/publish  as per guidelines of google
IOS: https://developer.apple.com/programs/enroll/  as per guidelines of apple
Website:  Place all files in public_html folder.
Proper documentation about the usage
Website: 
We have created common controller files used for website front end and sitepanel in apps/core folder (Private_controller, Public_controller, Admin_controller, Api_controller) names suggest the utility.
Common helpers for various funcnality used in the website front end and sitepanel are placed in apps/helpers.
Common view files for header and footer of the website front end are saved in apps/views folder.
Design related files such as css, js and images etc are saved in assets/designer forler, css, js, images and other files required for admin are saved in assets/developer and assets/sitepanel folder.
Website front end code files are saved in modules folder. Every folder contains controller, model and views.

##  Readme file 
###################
What is CodeIgniter
###################
CodeIgniter is an Application Development Framework - a toolkit - for people
who build web sites using PHP. Its goal is to enable you to develop projects
much faster than you could if you were writing code from scratch, by providing
a rich set of libraries for commonly needed tasks, as well as a simple
interface and logical structure to access these libraries. CodeIgniter lets
you creatively focus on your project by minimizing the amount of code needed
for a given task.
*******************
Release Information
*******************
This repo contains in-development code for future releases. To download the
latest stable release please visit the `CodeIgniter Downloads
Website:
<http://www.codeigniter.com/download>`_ page.
**************************
Changelog and New Features
*************************
You can find a list of all changes for each release in the `user
guide change log <https://github.com/bcit-ci/CodeIgniter/blob/develop/user_guide_src/source/changelog.rst>`_.
*******************
Server Requirements
*******************
linux Os ->  Centos 7.5
WHM/Cpnanel  server, 
Cloud Linux security enable
************
Installation
************
Please see the `installation section <http://www.codeigniter.com/user_guide/installation/index.html>`_
of the CodeIgniter User Guide.
*******
License
*******
Please see the `license
agreement <https://github.com/bcit-ci/CodeIgniter/blob/develop/user_guide_src/source/license.rst>`_.

*********
Resources
*********
-  `User Guide <http://www.codeigniter.com/docs>`_
-  `Language File Translations <https://github.com/bcit-ci/codeigniter3-translations>`_
-  `Community Forums <http://forum.codeigniter.com/>`_
-  `Community Wiki <https://github.com/bcit-ci/CodeIgniter/wiki>`_
-  `Community IRC <http://www.codeigniter.com/irc>`_
Report security issues to our `Security Panel <mailto:security@codeigniter.com>`_, thank you.
***************
Acknowledgement
***************
The CodeIgniter team would like to thank EllisLab, all the
contributors to the CodeIgniter project and you, the CodeIgniter user.
###################
APPS
###################
Android App:
	1.	Install Java
	2.	Install Android Studio 3.0+
	3.	Android SDK
	4.	Firebase Configure used for Firebase Cloud Messaging
	5.	Create Android Project
	6.	Language used Java and Kotlin
	7.	Copy / Paste all the provided files/code in your project
	8.	Sync your project with gradle/maven
	9.	Build / Run your project
iOS App :
	1.	Install XCode 10.0+
	2.	iOS OS 10.0+ 
	3.	Language used Swift
	4.	APNS Configure used for Apple Push Notification
	5.	Create iOS Project
	6.	Install CocoPOD for Third Party Libraries like 'Alamofire', '~> 4.0', 'IQKeyboardManagerSwift', ‘Kingfisher', '~> 4.10.0', 'ActionSheetPicker-3.0'
	7.	Copy / Paste all the provided files/code in your project
	8.	Build / Run your project

Set up documentation for Android, IOS & CodeIgniter

Setup document Website
Set environment in htaccess file (root) SetEnvIf HOST "^localhost" CI_ENV=development
Create dababase and set username, password and database in apps/config/dababase.php fle
Setup for Android App
	1.	Install Java
	2.	Install Android Studio 3.0+
	3.	Android SDK
	4.	Firebase Configure used for Firebase Cloud Messaging
	5.	Create Android Project
	6.	Language used Java and Kotlin
	7.	Copy / Paste all the provided files/code in your project
	8.	Sync your project with gradle/maven
	9.	Build / Run your project

Setup for iOS App
	1.	Install XCode 10.0+
	2.	iOS OS 10.0+ 
	3.	Language used Swift
	4.	APNS Configure used for Apple Push Notification
	5.	Create iOS Project
	6.	Install CocoPOD for Third Party Libraries like 'Alamofire', '~> 4.0', 'IQKeyboardManagerSwift', ‘Kingfisher', '~> 4.10.0', 'ActionSheetPicker-3.0'
	7.	Copy / Paste all the provided files/code in your project
	8.	Build / Run your project
	
iOS Used Library - 
	'ACFloatingTextfield Library'
	'Alamofire', '~> 4.0'
	'IQKeyboardManagerSwift'
	‘Kingfisher', '~> 4.10.0'
	'ActionSheetPicker-3.0'
	'CarbonKit'
	'SwiftyJSON'
	‘SVProgressHUD'
	'CryptoSwift'
	'SwiftyGif'
