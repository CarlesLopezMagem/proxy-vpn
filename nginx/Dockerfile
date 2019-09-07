FROM nginx:1.15.0-alpine

RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx
CMD sed -i.bak "s#host_redirect#$HOSTREDIRECT#" /etc/nginx/nginx.conf && nginx -g "daemon off;"