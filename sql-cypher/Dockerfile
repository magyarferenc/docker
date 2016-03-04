FROM magyarferenc/android-ndk

MAINTAINER Ferenc Magyar

RUN apt-get update -y && \
    apt-get install -y git
RUN cd /opt && \
    git https://github.com/sqlcipher/android-database-sqlcipher.git 
	
RUN cd android-database-sqlcipher && \
    make init
	
    
