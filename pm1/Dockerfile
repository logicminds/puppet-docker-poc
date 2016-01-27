FROM logicminds/pe-master:3.8
RUN yum install -y epel-release && yum -y install supervisor
COPY supervisord.conf /etc/supervisord.conf
EXPOSE 8140 61613
CMD ["/usr/bin/supervisord"]
