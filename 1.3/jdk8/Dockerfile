# FROM alpine:3.9
FROM openjdk:8-jdk-alpine3.8

# Kotlin
RUN apk add wget unzip && \
    cd /usr/lib && \
    wget https://github.com/JetBrains/kotlin/releases/download/v1.3.20-eap-100/kotlin-compiler-1.3.20-eap-100.zip && \
    unzip kotlin-compiler-*.zip && \
    rm kotlin-compiler-*.zip && \
    rm -f kotlinc/bin/*.bat && \
    apk del wget unzip