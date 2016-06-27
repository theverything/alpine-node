FROM alpine:3.4

RUN sed -i -e 's/v3\.4/edge/g' /etc/apk/repositories

RUN apk --update add --no-cache nodejs
