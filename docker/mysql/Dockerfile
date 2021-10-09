FROM mysql:5.7
ENV MYSQL_ROOT_PASSWORD=redmine
ENV MYSQL_USER=redmine
ENV MYSQL_PASSWORD=redmine
ENV MYSQL_DATABASE=redmine_development
COPY scripts/* /docker-entrypoint-initdb.d
