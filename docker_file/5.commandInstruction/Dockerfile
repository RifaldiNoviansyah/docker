FROM alpine:3

RUN mkdir hello
RUN echo "Hello World" > "hello/world.txt"

# ini akan dieksekusi ketika docker container dijalankan
CMD cat "hello/world.txt"