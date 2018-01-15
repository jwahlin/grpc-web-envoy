FROM envoyproxy/envoy-alpine

RUN apk update
RUN apk add ngrep

CMD ["envoy", "-l","trace", "-c","/etc/envoy/test.yaml"]
