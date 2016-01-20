FROM tomcat:6.0

ADD hive-service.war /usr/local/tomcat/webapps/hive-service.war

WORKDIR /opt
COPY hiveDataRestDir /opt/

RUN ls -l /opt
RUN ls -l /opt/hiveDataRest
RUN ls -l /opt/hiveDataRest/uat
RUN ls -l /opt/hiveDataRest/agrovoc

WORKDIR /usr/local/tomcat
CMD ["catalina.sh", "run"]