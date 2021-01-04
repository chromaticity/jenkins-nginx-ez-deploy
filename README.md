## NGINX and Jenkins ##

This repo contains the jenkins and nginx containers that I use for my home server for deployments.
NGINX functions as a reverse proxy for nginx.

Keep in mind that if you'd like to use this yourself, change the files within jenkins/nginx/conf.d/jenkins.conf to reflect whatever you're doing on your server.

to use, just do a 

```
docker-compose up --build
```

within the jenkins dir.

and jenkins will appear in whatever server you've got, provided you've changed the .conf file to match your server needs. 
