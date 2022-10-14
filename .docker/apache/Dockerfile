FROM httpd:2.4

RUN apt-get update && apt-get install -y --no-install-recommends make curl gcc pkg-config libglib2.0-dev awstats cron rsyslog rsync vim

CMD /usr/sbin/cron && httpd-foreground
