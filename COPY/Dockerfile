FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html

## COPY the code from local to container

COPY qi/  /usr/share/nginx/html/index.html
CMD ["nginx", "-g" ,"daemon off;"]