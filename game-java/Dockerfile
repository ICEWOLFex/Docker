FROM openjdk:11-jdk-slim

WORKDIR /the/workdir/paths

COPY game.java /the/workdir/paths/

RUN javac game.java

CMD ["java", "game.java"]