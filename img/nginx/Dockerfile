ARG VERSION=alpine
FROM nginx:$VERSION
ARG VERSION
ENV TIMEZONE Europe/London
RUN apk update && apk upgrade && apk --update --no-cache add bash
EXPOSE 80
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
