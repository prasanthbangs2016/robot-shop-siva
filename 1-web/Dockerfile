FROM nginx
#removing default nginx html file
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/nginx.conf
ENV CATALOGUE_HOST="catalogue"
ADD static /usr/share/nginx/html
