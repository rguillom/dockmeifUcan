FROM jetty

ADD sample.war /var/lib/jetty/webapps/

CMD ["java", "-Djava.io.tmpdir=/tmp/jetty","-jar","/usr/local/jetty/start.jar"]