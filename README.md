# log-generator-bin

- create the folders required for the log generator : "sudo mkdir /var/log/nginx_ingress/ /var/log/nginx_backend/ /var/log/nginx_frontend/  /var/log/mysql/"
- make them writeable "chmod 777  /var/log/nginx_ingress/ /var/log/nginx_backend/ /var/log/nginx_frontend/  /var/log/mysql/"
- start the log generator "java -jar log-generator-0.0.1-SNAPSHOT.jar"

