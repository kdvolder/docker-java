FROM      busybox:latest

# Copy testrun.sh files into the container

ADD	./testrun.sh       /tmp/
ADD     ./a                /tmp/a

RUN mkdir -p /usr/local/bin
RUN cp /tmp/testrun.sh /usr/local/bin/ && chmod +x /usr/local/bin/testrun.sh

CMD ["testrun.sh"]
