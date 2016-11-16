
<h2>This is a very simple example to control de GPIO outputs</h2>

<p>this small project is the continuity of a example to help you understand
GPIO functionality, you can take the example and modify if you want. 

<p>To install the aplication firstly, copy the project on your www folder 
and transfer the sql file to your database MySQL. 

<b>Important steps: Copy the folder and modify the file, "control.php" in line 6 and 7 for your MySQL credentials
<p>$MySQLUsername = "root";
<p>$MySQLPassword = "yourpassword";

<p> 1. mysql -u root -p < gpio.sql
<p> 2. go to you localhost gpiostatus/control.php
<p> 3. Log in as user: admin / password: admin 

</b>
<p>After all there a version manual mode <b>control_basic.php</b> where you can test also your status, feel free to modify 
as much as you want