FROM nginx
COPY ./default.conf /etc/nginx/conf.d/default.conf
COPY ./cert.pem /etc/nginx/conf.d/cert.pem
COPY ./key.pem /etc/nginx/conf.d/key.pem
EXPOSE 80
EXPOSE 443
CMD ["nginx", "-g", "daemon off;"]