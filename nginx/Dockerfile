FROM nginx:1.15.0-alpine

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d
COPY vpn.lesquerra.cat.crt /etc/nginx/vpn.lesquerra.cat.crt
COPY vpn.lesquerra.cat.key /etc/nginx/vpn.lesquerra.cat.key