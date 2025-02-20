FROM mysql:latest
ENV MYSQL_ROOT_PASSWOORD=concesionario1234
ENV MYSQL_DATABASE=concesionario
ENV MYSQL_USER=utilitario
ENV MYSQL_PASSWOORD=utilitario1234
COPY concesionario.sql /docker-entrypoint-initdb.d/
