ROM nginx:latest

# Copy config
COPY ./nginx.conf /etc/nginx/nginx.conf

# Copy website data
COPY --chown=www-data:www-data ./*.html /var/www/static/
RUN chmod 644 /var/www/static/*

USER root
EXPOSE 80
