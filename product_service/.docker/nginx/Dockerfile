FROM nginx:1.15.0-alpine
RUN apk update && apk add bash

RUN rm /etc/nginx/conf.d/default.conf
<<<<<<< HEAD
# RUN rm /etc/nginx/conf.d/nginx.conf
COPY ./nginx.conf /etc/nginx/conf.d
=======
# RUN chmod -R 777 /etc/nginx/conf.d
COPY ./nginx.conf2 /etc/nginx/conf.d/nginx.conf
>>>>>>> 02f0d910e873c5a72cfb3c08ce290097bf21e762
