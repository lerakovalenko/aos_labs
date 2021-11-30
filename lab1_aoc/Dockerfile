FROM ubuntu:20.04
RUN apt-get update
RUN apt-get install -y git
RUN apt-get install -y build-essential

COPY lab1_aoc.cpp .

RUN gcc -o lab1_aoc  lab1_aoc.cpp -lstdc++

ENTRYPOINT /lab1_aoc
