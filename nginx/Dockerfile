FROM nginx:stable-alpine
MAINTAINER mcravtov "mcravtov@gmail.com"
WORKDIR /etc/nginx
COPY conf/nginx.conf /etc/nginx
COPY conf/dev.com.conf /etc/nginx/sites-enabled/dev.com.conf
EXPOSE 80 443
CMD ["nginx", "-g", "daemon off;"]
