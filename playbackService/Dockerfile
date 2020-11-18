FROM openjdk:11
WORKDIR /Users/max_slob/git/PlaybackService
COPY target/playbackService-0.0.1-SNAPSHOT.jar service.jar
EXPOSE 8087
CMD ["java", "-jar", "service.jar"]