# kafka-manager-el7-spec-rpm

# Building
    wget https://github.com/yahoo/kafka-manager/archive/1.3.0.8.zip && unzip 1.3.0.8.zip
    cd ./kafka-manager-1.3.0.8
    ./sbt clean dist
    cp target/universal/kafka-manager-1.3.0.8.zip ${RPMBUILD}/SOURCES
