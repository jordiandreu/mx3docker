#FROM debian:stretch
#RUN apt-get update
#RUN apt-get install -y git vim
#RUN apt-get install -y python-qt4
#RUN apt-get install -y python-gevent
#RUN apt-get install -y python-louie
#RUN apt-get install -y python-jsonpickle
#RUN apt-get install -y python-numpy
#RUN apt-get install -y python-scipy
#RUN apt-get install -y python-matplotlib
#RUN apt-get install -y python-suds pymca
#RUN apt-get install -y python-yaml
#RUN apt-get install -y python-pydispatch

#RUN mkdir -p /MXCuBE/mxcube
#WORKDIR /MXCuBE/mxcube
FROM mx3_deb9_qt4


ENV DEBIAN_FRONTEND noninteractive
## install mysql server 
#RUN apt-get install -y default-mysql-server
##install tango-db 
#RUN apt-get install -y tango-db
##install tango-test DS 
#RUN apt-get install -y tango-test
## install sardana dependencies
#RUN apt-get install -y python-pytango
#ENV TANGO_HOST=localhost:10000 

RUN apt-get install -y python-sardana

