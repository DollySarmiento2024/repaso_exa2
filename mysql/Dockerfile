FROM mysql:latest

# contraseña root base de datos
ENV MYSQL_ROOT_PASSWORD=fernanda

#nombre base de datos
ENV MYSQL_DATABASE=concesionario

# usuario y contraseña base de datos
ENV MYSQL_USER=root
ENV MYSQL_PASWORD=

COPY concesionario.sql /docker-entrypoint-initdb.d/
