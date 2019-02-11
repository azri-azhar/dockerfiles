
FROM loadimpact/k6 as k6
FROM alpine:edge
RUN apk update;apk add nghttp2;apk add iperf3; apk add curl; apk add tcpdump
FROM alpine:edge
RUN apk update;apk add nghttp2
ENTRYPOINT ["/usr/bin/h2load"]
