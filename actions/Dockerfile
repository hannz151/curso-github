FROM alpine:latest
RUN apk add --no-cache \
bash \
ca-certificates \
curl \
jq

COPY entrypoint.sh /entrupoint.sh

ENTRYPOINT ["/entrypoint.sh"]