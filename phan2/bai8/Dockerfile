FROM postgres:15
COPY init.sql /docker-entrypoint-initdb.d/
ENV POSTGRES_PASSWORD=mysecretpassword
EXPOSE 5432