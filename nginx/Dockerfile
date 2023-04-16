FROM nginx:alpine-slim

RUN rm /etc/nginx/conf.d/*

COPY ./nginx.conf /etc/nginx/conf.d/

VOLUME /var/log/nginx/log

CMD [ "nginx", "-g", "daemon off;" ]
