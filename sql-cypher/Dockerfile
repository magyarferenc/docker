FROM magyarferenc/android-ndk

MAINTAINER Ferenc Magyar

RUN apt-get update -y && \
    apt-get install -y git
RUN cd /opt && \
    git clone https://github.com/sqlcipher/android-database-sqlcipher.git 
	
RUN apt-get install -y build-essential    
RUN cd /opt/android-database-sqlcipher && make init

	
    
