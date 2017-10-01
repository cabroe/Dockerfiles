FROM alpine:latest

MAINTAINER Marc Lennox <marc.lennox@gmail.com>

# Set environment variables.
ENV \
  TERM=xterm-color

# Install packages.
RUN \
  apk --update add bash coreutils curl nano procps rsync tar wget openrc && \
  rm -rf /var/cache/apk/*

# Set the default command.
CMD ["/bin/bash"]