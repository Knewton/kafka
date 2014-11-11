Apache Kafka - Knewton-specific instructions
============================================

### Building a jar ###
    ./gradlew -PscalaVersion=2.10.1 jar
This should produce core/build/libs/kafka_2.10-0.8.1.1-KNEWTON.jar.

### Uploading a jar to Nexus. ###
1. Go to https://nexus.knewton.net/nexus and login.
2. Click the "Repositories" link.
3. Click the "Releases" repository.
4. Click the "Artifact Upload" tab.
5. Select "GAV Definition: From POM".
6. Click "Select POM to Upload..." and select kafka_2.10-0.8.1.1-KNEWTON.pom.
7. Click "Select Artifact(s) to Upload..." and select core/build/libs/kafka_2.10-0.8.1.1-KNEWTON.jar.
8. Click "Upload Artifact(s)".
