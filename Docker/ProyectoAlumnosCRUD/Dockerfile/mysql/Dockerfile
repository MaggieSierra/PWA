FROM mysql:latest

ENV MYSQL_DATABASE="lista_alumnos"
ENV MYSQL_ROOT_PASSWORD="root"

COPY lista_alumnos.sql /docker-entrypoint-initdb.d/lista_alumnos.sql