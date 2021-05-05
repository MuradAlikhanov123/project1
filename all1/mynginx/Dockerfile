
FROM nginx:alpine
RUN apk update
COPY nginx.conf /etc/nginx/nginx.conf
COPY site1.conf /etc/nginx/conf.d/default.conf
COPY site1.html /usr/share/nginx/html/index.html
EXPOSE 80 443
ENTRYPOINT ["nginx","-g","daemon off;"]
