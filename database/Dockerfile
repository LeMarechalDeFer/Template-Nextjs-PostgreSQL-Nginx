# Use the official PostgreSQL image as a parent image
FROM postgres:latest


# Copy custom initialization scripts
COPY ./remember_db.sql /docker-entrypoint-initdb.d/

