FROM alpine:3.6

ADD https://github.com/leenux/docker-library/blob/master/nats-streaming/nats-streaming-server /nats-streaming-server
RUN chmod +x /nats-streaming-server

RUN mkdir -p /data/nats-streaming/

# Expose client and management ports
EXPOSE 4222 8222

# Run with default memory based store
#ENTRYPOINT ["/nats-streaming-server"]
