# Java-learing in Ubuntu18.04 
## java10.0.2 install
1. Download from https://www.oracle.com/technetwork/java/javase/downloads/jdk10-downloads-4416644.html
2. Unzip (tar -zxvf xxx.tar.gz)
3. Configuring environment variables
```
export JAVA_HOME=/usr/local/java/jdk1.8.0_25 (your install path)
export JRE_HOME=${JAVA_HOME}/jre  
export CLASSPATH=.:${JAVA_HOME}/lib:${JRE_HOME}/lib  
export PATH=${JAVA_HOME}/bin:$PATH
```
## tomcat install
1. Download from http://tomcat.apache.org/download-90.cgi
2. Unzip (tar -zxvf xxx.tar.gz)
3. 
(a problem with tomcat started, but an error appear in the 127.0.0.1:8080)
## maven install
1. Download from https://maven.apache.org/download.cgi
2. Unzip (tar -zxvf xxx.tar.gz)
3. Configuring environment variables
```
export M2_HOME=~/Programs/apache-maven
export PATH=.:$M2_HOME/bin:$PATH
```

Continuous update...
