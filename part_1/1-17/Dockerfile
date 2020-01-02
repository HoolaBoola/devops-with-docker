FROM ubuntu
FROM rust:slim

WORKDIR /mydir
COPY ./start /mydir/

RUN cargo build

CMD cargo run && /bin/bash 
