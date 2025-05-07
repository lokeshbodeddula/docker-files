FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html 
ADD https://github.com/lokeshbodeddula/Docker-Zero-to-Hero/blob/main/README.md /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"] 