FROM ub-java:3.0
FROM log5:fwb

ENV DEBIAN_FRONTEND noninteractive
CMD /usr/share/logstash/bin/logstash -f /test3.conf --path.data /PATH1 ;while true ; do sleep 100; done;
EXPOSE 5000 5001 9600 5044 5002

