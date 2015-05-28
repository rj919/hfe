# Comment Section
FROM ubuntu:14.04
MAINTAINER RC42 <richard@collectiveacuity.com>
RUN apt-get update
RUN apt-get install -y emacs
RUN apt-get install -y git
RUN apt-get install -y cron
RUN apt-get install -y python3-pip
RUN pip3 install python-dateutil
RUN pip3 install pytz
RUN pip3 install tzlocal
RUN pip3 install mandrill
RUN pip3 install twilio
RUN pip3 install cassandra-driver