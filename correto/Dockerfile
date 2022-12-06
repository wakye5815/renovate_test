FROM amazoncorretto:11-alpine3.16

# renovate: datasource=repology depName=alpine_3_16/curl versioning=loose
ENV CURL_VERSION="7.80.0-r4"

RUN apk update 
RUN apk add --no-cache --repository http://dl-cdn.alpinelinux.org/alpine/v3.15/main curl="${CURL_VERSION}"

# RUN curl -o /usr/local/bin/jq -L https://github.com/stedolan/jq/releases/download/jq-1.5/jq-linux64 && sudo chmod +x /usr/local/bin/jq