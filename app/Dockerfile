FROM tomcat:8-jre11
LABEl "project"="Vprofile"
LABEL "Author"="Kavindu"
RUN rm -rf /ur/local/tomcat/webapps/*
COPY target/vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh","run"]
WORKDIR /ur/local/tomcat/
VOLUME /ur/local/tomcat/webapps/