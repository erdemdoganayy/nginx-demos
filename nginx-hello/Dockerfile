FROM nginx:mainline-alpine
FROM postgres
RUN rm /etc/nginx/conf.d/*
ADD hello.conf /etc/nginx/conf.d/
ADD index.html /usr/share/nginx/html/
FROM mysql
