FROM apache/drill:1.18.0

WORKDIR /opt/drill/jars/3rdparty

COPY jars/hadoop-azure-2.7.7.jar hadoop-azure-2.7.7.jar
COPY jars/azure-storage-8.0.0.jar azure-storage-8.0.0.jar

WORKDIR /opt/drill

COPY conf-custom ./conf

WORKDIR /