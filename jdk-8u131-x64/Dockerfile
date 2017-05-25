FROM airdock/oracle-jdk:latest
MAINTAINER Kirill Bychkov <kb@na.ru>

RUN apt-get update \
	&& apt-get install -y fakeroot libxml2 libxml2-utils \
	&& rm -rf /var/lib/apt/lists/*