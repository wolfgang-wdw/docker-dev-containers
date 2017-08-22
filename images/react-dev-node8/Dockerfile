FROM centos:latest

RUN yum install -y nc
RUN curl --silent --location https://rpm.nodesource.com/setup_8.x | bash -
RUN yum install -y nodejs
RUN npm install -g create-react-app

WORKDIR /usr/src/app
