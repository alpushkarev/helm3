FROM nginx:1.29.3-alpine3.22

COPY nginx.conf /etc/nginx/nginx.conf

WORKDIR /usr/share/nginx/html
COPY dist/ .

EXPOSE 4200

CMD ["nginx", "-g", "daemon off;"]
