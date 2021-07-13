---------------------------------------------------------------------------------
REQUIREMNT
------------

Nginx		: Application server 
PHP			: Server side language 
CI			: Codeignator freamwork
MySql 		: Dataaseused for store provide json data
HTML & CSS	: Front end changes
JS 			: Scripting language 
Jquery 		: Use JS lib for AJAX and other operations on the frontend 

---------------------------------------------------------------------------------
SETUP PROJECT  (follow below steps)
--------------
Extract "Source Code.zip" file for setup code

Set permistion 777 to "writable" folder in root directory 
path: : vistaprint/writable

Add host entry for domain   Eg:  127.0.0.1   vistatest.com

This project tested on Nginx and ubuntu system, sharing video.

Create DB "vistaroom" and import DB script in DB
Table name check in the script.
DB config details update in file "vistaroom/app/Config/Database.php"

Enter the domain in the browser address bar.


---------------------------------------------------------------------------------
MY TESTING 
--------------

1] Domain name: http://vistatest.com/

2] Load new job list on the scroll bar at the bottom 

3] On click left side job details fetch using ajax and load job description in the right section.
