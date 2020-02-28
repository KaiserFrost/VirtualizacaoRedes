FROM ubuntu:latest
LABEL maintainer = "TPVR"
RUN apt-get update && apt-get upgrade -y
RUN apt-get install nginx -y
EXPOSE 8888
VOLUME [ "/home/output" ]
CMD ["nginx","-g","daemon off;"]


