FROM registry.access.redhat.com/devtools/go-toolset-rhel7:latest

USER root

RUN mkdir /usr/local/app

ADD src/ /usr/local/app/

WORKDIR /usr/local/app/

RUN /opt/rh/go-toolset-1.11/root/usr/bin/go build main.go

EXPOSE 8080

USER 1001

CMD ["/usr/local/app/main"]
