FROM nginx:1.15.6
COPY nginx.conf /etc/nginx/conf.d/default.conf
HEALTHCHECK --interval=5m --timeout=3s \
  CMD curl -f http://localhost/ || exit 1