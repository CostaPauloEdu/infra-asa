FROM nginx:latest 

WORKDIR /var/www/application

COPY ./config/vhost.conf /etc/nginx/conf.d/default.conf

RUN chmod 755 -R /var/www/application

EXPOSE 80

EXPOSE 443

ENTRYPOINT [ "nginx" ]

CMD [ "-g", "daemon off;" ]