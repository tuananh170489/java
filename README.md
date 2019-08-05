# Install oracle-java from source
### Download java
```
wget jdk-7u80-linux-x64.tar.gz
```
### Extract
```
tar xzvf jdk-7u80-linux-x64.tar.gz -C /usr
```
### Install
Set environment on /etc/environment
```
JAVA_HOME=/usr/lib/jvm/jre/bin/java
```
Install the alternative for java
```
update-alternatives --install /usr/bin/java java /usr/lib/jvm/jre/bin/java 1
```
