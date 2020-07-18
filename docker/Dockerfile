FROM python

LABEL version="1.0"
LABEL description="Extending python image adding a few more packages"

#ENV http_proxy=
#ENV https_proxy=

RUN apt-get update
RUN apt-get install vim-tiny -y
RUN apt-get install -y protobuf-compiler

# I know you are not supposed to do this, it's not very docker-like
ENTRYPOINT ["tail", "-f", "/dev/null"]

