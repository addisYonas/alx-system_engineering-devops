# Web infrastructure design

Website Infrastructure means the servers, networks, and other underlying infrastructure supporting the Website.


## 0. Simple web stack 
You must use:

    1 server
    1 web server (Nginx)
    1 application server
    1 application files (your code base)
    1 database (MySQL)
    1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8
## 1.Distributed web infrastructure 
You must add:

    2 servers
    1 web server (Nginx)
    1 application server
    1 load-balancer (HAproxy)
    1 set of application files (your code base)
    1 database (MySQL)
## 2.Secured and monitored web infrastructure 
You must add:

    3 firewalls
    1 SSL certificate to serve www.foobar.com over HTTPS
    3 monitoring clients (data collector for Sumologic or other monitoring services)

## Authors

- yonas gebreyesus 
- email:addyonas@gmail.com


