FROM adoptopenjdk:14-jdk-hotspot-bionic
ARG VERSION="1.0.1"
WORKDIR /usr/local/src
RUN curl -OL https://github.com/rayokota/kareldb/releases/download/kareldb-parent-${VERSION}/kareldb-server-${VERSION}-package.tar.gz && \
    tar xzvf kareldb-server-${VERSION}-package.tar.gz && \
    rm kareldb-server-${VERSION}-package.tar.gz