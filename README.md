# Ansible-nginx-TLS-webserver
# to create TLS key and certificate
openssl req -x509 -nodes -days 3650 -newkey rsa:2048 -subj /CN=172.31.32.5 -keyout files/nginx.key -out files/nginx.crt
