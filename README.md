# vistaroomTest
Praful test code

---------------------------------------------------------------------------------
REQUIREMNT
------------

Nginx         : Application server <br>
PHP           : Server side language <br>
CI            : Codeignator freamwork<br>
MySql         : Dataaseused for store provide json data<br>
HTML & CSS    : Front end changes<br>
JS            : Scripting language <br>
Jquery        : Use JS lib for AJAX and other operations on the frontend <br>

---------------------------------------------------------------------------------
SETUP PROJECT  (follow below steps)
--------------
Extract "Source Code.zip" file for setup code

Set permistion 777 to "writable" folder in root directory 
path: : vistaprint/writable

Add host entry for domain   Eg:  127.0.0.1   vistatest.com

"vistaroom.conf" file for nginx, Need to update "server_name", "root", "fastcgi_pass"  this param as per your system


This project tested on Nginx and ubuntu system, for demo video please check "Local demo.webm".

Create DB "vistaroom" and import DB script in DB
Table name check in the script "vistaroom.sql" file.
DB config details update in file "vistaroom/app/Config/Database.php"

Enter the domain in the browser address bar.


---------------------------------------------------------------------------------
MY TESTING 
--------------

1] Domain name: http://vistatest.com/

2] Load new job list on the scroll bar at the bottom 

3] On click left side job details fetch using ajax and load job description in the right section.
