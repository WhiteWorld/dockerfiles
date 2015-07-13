FROM java:7-jre

MAINTAINER White World "ljq258@gmail.com"


RUN cd /opt && wget http://caucho.com/download/resin-4.0.44.zip &&  unzip resin-pro-4.0.44.zip && rm resin-pro-4.0.44.zip && mv resin-pro-4.0.44 resin

# Add config file and war
# ADD resin.xml /opt/resin/conf/
# ADD mihome.war /opt/resin/webapps/war/

# port
# EXPOSE 80
