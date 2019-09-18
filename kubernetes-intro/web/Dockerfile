FROM nginx:stable
COPY nginx.conf /etc/nginx/nginx.conf
RUN  usermod -u 1001 nginx
RUN  mkdir -p  /app /var/run/nginx && chown nginx:nginx /app /var/run/nginx /var/cache/nginx
USER 1001
EXPOSE 8000