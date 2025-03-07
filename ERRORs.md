# 503 - service temporarily unavailable
   the server is overloaded or down for maintenance.

# 403 - Forbidden 
   the server understand the request but cant provide aacess to the page for some reasons its usually due to permisions  issue or configuration problem 

   # troubleshooting

   1. check file permission - ls -l /var/www/html
   2. verify the nginx configuration - /etc/nginx/nginx.conf
   3. check for index file - index.html
   4.  review error logs - /var/log/nginx/error.log 
   
