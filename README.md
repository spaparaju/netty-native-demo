# Instant Netty startup using GraalVM's Native Image Generation

Instructions to follow:

1. Close this repository
2. cd netty-native-demo
3. docker build -t test-netty-server-with-quarkus:1 .
4. docker run -d --rm -p 8080:8080 test-netty-server-with-quarkus:1
