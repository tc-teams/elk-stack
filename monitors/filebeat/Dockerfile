FROM docker.elastic.co/beats/filebeat:8.0.0

COPY filebeat.yml /usr/share/filebeat/filebeat.yml

USER root

RUN chown root:filebeat /usr/share/filebeat/filebeat.yml

USER filebeat