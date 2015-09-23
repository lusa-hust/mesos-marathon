FROM ubuntu:14.04
# install postgres
RUN sudo apt-get install -y postgresql postgresql-contrib
# config postgres
COPY ./pg_hba.conf /tmp/
COPY ./postgresql.conf /tmp/
RUN cp /tmp/* /etc/postgresql/9.3/main/
