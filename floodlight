#!/bin/bash
#Program:
# Creating a floodlight controller.
#History:
# 2015/12/12 Liu
PATH=/bin:/sbin/:/usr/bin:/usr/sbin:/usr/local/bin:/usr/local/sbin:~/bin
export PATH

apt-get install build-essential default-jdk ant python-dev
git clone git://github.com/floodlight/floodlight.git
cd floodlight
git checkout stable
ant
java -jar target/floodlight.jar
