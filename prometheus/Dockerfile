FROM prom/prometheus:latest
# https://hub.docker.com/r/prom/prometheus/tags/

COPY conf /etc/prometheus/

ENTRYPOINT [ "/etc/prometheus/docker-entrypoint.sh" ]
CMD        [ "--config.file=/etc/prometheus/prometheus.yml", \
             "--storage.tsdb.path=/prometheus" ]
