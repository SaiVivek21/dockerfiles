FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/SaiVivek21/dockerfiles/refs/heads/main/RUN/Dockerfile  /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/index.html
ADD sample-1.tar /tmp/
CMD ["nginx" , "-g" , "daemon off;"]
