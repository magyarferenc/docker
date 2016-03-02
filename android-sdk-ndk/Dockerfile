FROM magyarferenc/android-sdk


# Installs Android NDK
ENV ANDROID_NDK_FILENAME android-ndk-r10e-linux-x86_64.bin
ENV ANDROID_NDK_VERSION r10e
ENV ANDROID_NDK_URL http://dl.google.com/android/ndk/${ANDROID_NDK_FILENAME}
ENV NDK_HOME /opt/android-ndk-${ANDROID_NDK_VERSION}
ENV PATH ${PATH}:${NDK_HOME}
RUN cd /opt && \
    wget -q ${ANDROID_NDK_URL} && \
    chmod a+x ${ANDROID_SDK_FILENAME} && ./${ANDROID_NDK_FILENAME} && \
    rm ${ANDROID_NDK_FILENAME} 
    
