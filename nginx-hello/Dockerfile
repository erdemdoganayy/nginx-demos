FROM nginx:mainline-alpine
COPY . .
RUN rm /etc/nginx/conf.d/*
COPY . .
ADD hello.conf /etc/nginx/conf.d/
COPY . .
ADD index.html /usr/share/nginx/html/
COPY . .
