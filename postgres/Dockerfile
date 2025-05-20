FROM postgres:17.2-alpine

ENV POSTGRES_DB=db \
   POSTGRES_USER=usr \
   POSTGRES_PASSWORD=pwd

COPY Table.sql /docker-entrypoint-initdb.d/Table.sql
COPY Init.sql /docker-entrypoint-initdb.d/Init.sql