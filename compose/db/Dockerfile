# pull official base image
FROM postgres:14-alpine

# run create.sql on init
ADD ./compose/db/create.sql /docker-entrypoint-initdb.d