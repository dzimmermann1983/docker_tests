# docker_tests

This project has a Dockerfile which installs you a postgres database with two databases, one for testing purposes and one for development purposes.

In the pom.xml the docker-maven-plugin is integrated into your build phase, so everytime you build your project a docker container is created and started at the pre-integration-phase, and stopped in the post-integration-phase.
