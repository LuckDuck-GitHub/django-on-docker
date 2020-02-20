FROM nginx:1.17.4-alpine
#drop nginx config and copy new
RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d