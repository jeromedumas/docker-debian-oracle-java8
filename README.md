# Debian Docker image with Oracle Java 8

Basic Docker image to run Java applications, based on Debian Jessie. This image is patched with Java Cryptographic Extension (JCE) Unlimited Strength Jurisdiction Policy Files.

Based on [`davidcaste/docker-debian-oracle-javaa`](https://hub.docker.com/r/davidcaste/debian-oracle-java/) Docker image.

### Build

docker build -t debian-oracle-java8 .

### Usage

Example:

    docker run -it --rm debian-oracle-java8 java -version
