# FROM eclipse-temurin:21-jdk-alpine
# # Build Main.java with JDK
# # TODO : in next steps (not now)

# FROM eclipse-temurin:21-jre-alpine
# # Copy resource from previous stage
# COPY Main.class /app/Main.class
# # Run java code with the JRE
# # TODO : in next steps (not now)

FROM openjdk:21-jdk
# TODO:  Add the compiled java (aka bytecode, aka .class)
COPY Main.class Main.class
# TODO: Run the Java with: “java Main” command. 
CMD ["java", "Main"]