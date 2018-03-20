# README
## Description
It's a deployed-practice at remote server
## url
ip: 13.115.182.45
[http://13.115.182.45](http://13.115.182.45)
##ssh
you can login as folloing command

```sudo ssh grader@13.115.182.45 -i ~/.ssh/udacity -p 2200```
## Confiuration
1. add new user grader as a sudo accesser.
2. disable root login.
3. install ufw and only allow port of ssh/ntp/http
4. update applications
5. change timezone
6. change ssh port
7. install python environment
8. install PostgreSQL and add new user catalog
9. add wsgi.py/catalog.conf(apache config)
## Software
1. ufw
2. postgresql(database)
3. virtualenv(python environment)
4. libapache2-mod-wsgi(wsgi support)
5. apache2(server)
6. git
7. python-pip
## Referrence
- [https://stackoverflow.com/questions/18392741/apache2-ah01630-client-denied-by-server-configuration](https://stackoverflow.com/questions/18392741/apache2-ah01630-client-denied-by-server-configuration)
- [http://www.bogotobogo.com/python/Flask/Python_Flask_HelloWorld_App_with_Apache_WSGI_Ubuntu14.php](http://www.bogotobogo.com/python/Flask/Python_Flask_HelloWorld_App_with_Apache_WSGI_Ubuntu14.php)
- [https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)

