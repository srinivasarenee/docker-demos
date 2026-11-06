FROM almalinux:9
RUN dnf install nginx -y
LABEL COURSE="DOCKER_FDE"
LABEL NAME="FDE"
EXPOSE 80
COPY index.html /usr/share/nginx/html/
CMD [ "nginx", "-g", "daemon off;" ]
