getting github actions to deploy to raspberrypi 

https://dev.to/hnrq/using-github-actions-to-deploy-a-web-page-to-raspberry-pi-46bi

docker run --name some-nginx -p80:80 -v ~/html:/usr/share/nginx/html:ro -d nginx

add .ssh/id_rsa to secret in github actions
add .ssh/id_rsa.pub to authorised_keys on raspberry pi