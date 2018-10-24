FROM tomcat

EXPOSE 8080

RUN rm -rf /usr/local/tomcat/webapps/* && \
    mkdir -p /opt/palas/palasFileServer/contractFiles && \
    mkdir -p /opt/palas/palasFileServer/reports

COPY PALAS2.0.war /usr/local/tomcat/webapps/palas.war