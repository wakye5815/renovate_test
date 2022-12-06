FROM amazoncorretto:18.0.2-alpine3.15

# renovate: datasource=repology depName=alpine_3_15/curl versioning=loose
ENV CURL_VERSION="7.79.1-r3"

RUN apk update 
RUN apk add --no-cache --repository http://dl-cdn.alpinelinux.org/alpine/v3.14/main curl="${CURL_VERSION}"

# RUN curl -o /usr/local/bin/jq -L https://github.com/stedolan/jq/releases/download/jq-1.5/jq-linux64 && sudo chmod +x /usr/local/bin/jq