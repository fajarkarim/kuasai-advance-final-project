FROM mysql:5.7
HEALTHCHECK --interval=5m --timeout=30s --start-period=5s --retries=3 \
    CMD mysqladmin ping -h localhost