FROM phpmyadmin/phpmyadmin:4.8.5
HEALTHCHECK --interval=5m --timeout=3s \
  CMD curl -f http://localhost/ || exit 1