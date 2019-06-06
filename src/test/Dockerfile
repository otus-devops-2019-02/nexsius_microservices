FROM ubuntu:16.04
ENV DATABASE_URL post_db
RUN apt-get update && apt-get install -y iputils-ping
CMD ["ping", "DATABASE_URL"]
