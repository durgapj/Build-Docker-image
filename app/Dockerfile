FROM tomcat:8-jre11
LABEL "project"="vprofile"
LABEL  "author"="durgapj"
RUN rm -rf /usr/local/tomcat/webapps/*
COPY target/vprofile-v2.war /usr/tomcat/webaps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh" ,"run"]
WORKDIR /usr/local/tomcat/
VOLUME /usr/local/tomcat/webapps
