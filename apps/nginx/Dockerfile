FROM nginx

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx_ssl.conf /etc/nginx/conf.d
COPY ssl /etc/ssl/

EXPOSE 3000