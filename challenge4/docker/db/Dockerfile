# Use the official MariaDB image as base
FROM mariadb

# copy the init script to the /docker-entrypoint-initdb.d 
COPY init/init.sql /docker-entrypoint-initdb.d
