FROM nginx:1.19.4-alpine

WORKDIR /tmp/

RUN whoami

EXPOSE 80
ENTRYPOINT ["nginx","-g","daemon off;"]