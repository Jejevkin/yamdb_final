FROM nginx:1.19.6-alpine

WORKDIR /static
RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d
RUN chown -r nginx:nginx /static
# тут поменять