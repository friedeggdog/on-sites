**Instructions**

Copy the /etc/hosts config

Start and setup apache using the configuration given in etc\httpd\conf\extra\httpd-vhosts.conf

Run docker-compose up --build --scale mess1=3 --scale mess2=3 --scale mess3=3 

"script.sh" can be used to test the load balancing
