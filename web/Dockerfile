FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
# RUN rm -rf /etc/nginx/nginx.conf
# RUN rm -rf /etc/nginx/conf.d/default.conf
# Copy roboshop.conf /etc/nginx/nginx.conf
Copy roboshop.conf /etc/nginx/default.d/roboshop.conf
ADD static /usr/share/nginx/html/
 