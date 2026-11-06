FROM nginx:1.29.7
LABEL COURSE="DOCKER_FDE"
LABEL NAME="FDE"
ENV DB_HOST="https://db.test.com"
ENV DB_USER="DBUSER" \
    DB_PWD="test123"
EXPOSE 80
COPY qi/ /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/daws-88s/roboshop-documentation/refs/heads/main/02-catalogue.MD /tmp/
ADD sample-1.tar /tmp/