ARG NGINX_VERSION
FROM nginx:${NGINX_VERSION}

COPY default.conf /etc/nginx/conf.d/default.conf

RUN echo 'fastcgi_param HTTPS $scheme_https;' >> /etc/nginx/fastcgi_params

WORKDIR /etc/nginx