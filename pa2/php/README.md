
### One Quick Note

Since you are extending functionality from your website in PA1, copy and paste your previous code into the new directory.
ErrorLog "/var/www/html/mattman/admin/pa1/php/httpd-error.log"
When you do this, you will have to modify several lines of httpd.conf under conf folder. whichever line that contain "pa1" should change into the proper path. 

For example, assume you put pa2 folder is located at GroupXX/admin/pa2_pak0sbtdg1i 
The orginal line 372 in httpd.conf: ErrorLog "/var/www/html/GroupXX/admin/pa1/php/httpd-error.log" 
should change into ErrorLog "/var/www/html/GroupXX/admin/pa2_pak0sbtdg1i/php/httpd-error.log" 
