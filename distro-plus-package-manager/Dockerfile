FROM ubuntu:15.10

RUN apt-get update && apt-get install --no-install-recommends -y openjdk-8-jre

ADD Main.class /

CMD ["java", "-cp", "/", "Main"]
