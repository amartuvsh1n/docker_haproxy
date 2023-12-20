# docker with haporxy

## gen ssl
```bash
mkdir certs
openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout certs/nginx-selfsigned.key -out certs/nginx-selfsigned.crt
openssl dhparam -out certs/dhparam.pem 1024
```
