FROM nginx
RUN rm -rf /usr/share/nginx/html/*
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf
ADD static-web /usr/share/nginx/html/
