FROM maven:3.8.5-openjdk-11-slim
RUN mkdir /app
WORKDIR /app
COPY . .
RUN mvn clean install
CMD mvn spring-boot:run