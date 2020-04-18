FROM nginx:alpine
RUN rm /etc/nginx/sites-enabled/default
COPY ./compose/production/nginx/oursite.conf /etc/nginx/sites-enabled/default
