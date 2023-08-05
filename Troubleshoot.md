## Start Apache, Error: Apache shutdown unexpectedly
  Stop iis manager<br>
  XAMPP Apache Config > httpd.conf<br>
Change default port 80 to 8080
```
  Search "80"
  Change Port 80 to 8080
  Change listen 80 to 8080
  ServerName localhost:8080
```
## GD Error
In PHP, GD is the library of image functions<br>
Uncaught Error: Call to undefined function imagecreatetruecolor()<br>
C:\xampp\php\php.ini<br>
Search "gd"<br>
remove ";" before ";extension=gd"<br>
