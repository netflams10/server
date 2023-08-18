## Nginx Docs
## https://docs.nginx.com/

## Note: make sure you write the path out in full
## sudo ln -s /etc/nginx/sites-available/dashboard.example.com /etc/nginx/sites-enabled/dashboard.example.com

## sudo nginx -t
## sudo systemctl stop nginx

## certbot --nginx
## Then choose number seperated by comma

## sudo nano /var/log/nginx/error.log
## sudo nano /var/log/syslog

## checking on port 80
## lsof -i :80 or sudo fuser -k 80/tcp

## sudo pkill -f nginx & wait $!
## sudo systemctl start nginx

## List nginx status
## grep -r listen /etc/nginx/*

## Remove nginx
## sudo apt remove nginx
## sudo apt purge nginx
## apt-get autoremove
## sudo apt-get remove --purge nginx*
## sudo apt-get autoremove --purge

## Install nginx -> certbot
## Docs -->> https://geekflare.com/setup-nginx-with-lets-encrypt-cert/
# apt-get install software-properties-common
# add-apt-repository ppa:certbot/certbot
# apt-get update
# apt-get install python3-certbot-nginx
