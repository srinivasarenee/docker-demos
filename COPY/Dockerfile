FROM nginx:1.29.7
LABEL COURSE="DOCKER_FDE"
LABEL NAME="FDE"
EXPOSE 80
COPY qi/ /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/daws-88s/roboshop-documentation/refs/heads/main/02-catalogue.MD /tmp/
ADD sample-1.tar /tmp/