FROM postgres:10.6-alpine
ENV POSTGRES_DB foodpolls
COPY ./init.sql /docker-entrypoint-initdb.d/
