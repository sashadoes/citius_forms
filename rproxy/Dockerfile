FROM nginx
COPY nginx.conf.template /etc/nginx/nginx.conf.template
COPY docker-entrypoint.sh /
RUN chmod +x /docker-entrypoint.sh
ENTRYPOINT ["/docker-entrypoint.sh"]
EXPOSE 80
