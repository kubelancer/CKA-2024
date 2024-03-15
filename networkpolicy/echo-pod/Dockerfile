FROM nginx:alpine-slim
COPY index.html /usr/share/nginx/html/
COPY default.conf /etc/nginx/conf.d/
RUN apk add curl
RUN apk add wget
