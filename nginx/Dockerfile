# FROM nginx:stable

# RUN rm /etc/nginx/conf.d/default.conf
# COPY nginx.conf /etc/nginx/conf.d


FROM jwilder/nginx-proxy:latest
COPY vhost.d/default /etc/nginx/vhost.d/default
COPY custom.conf /etc/nginx/conf.d/custom.conf