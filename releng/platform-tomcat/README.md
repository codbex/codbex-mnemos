# codbex-mnemos-tomcat

The `codbex` mnemos `tomcat` package

To build the docker image:

    docker build -t codbex-mnemos-tomcat:latest .

To run a container:

    docker run --name codbex --rm -p 8080:8080 -p 8081:8081 codbex-mnemos-tomcat:latest

To tag the image:

    docker tag codbex-mnemos-tomcat codbex.jfrog.io/codbex-docker/codbex-mnemos-tomcat:latest

To push to JFrog Container Registry:

    docker push codbex.jfrog.io/codbex-docker/codbex-mnemos-tomcat:latest

To pull from JFrog Container Registry:

    docker pull codbex.jfrog.io/codbex-docker/codbex-mnemos-tomcat:latest
