# Microservice Archetype


A simple archetype to generate a Spring Boot Starter Web application with:

 * Docker Build
 * Kubernets or Openshift Deployment script (TODO)
 

### How to use:


    mvn archetype:generate                                  \
      -DarchetypeGroupId=br.com.fredericci.archetype        \
      -DarchetypeArtifactId=microservice-archetype          \
      -DarchetypeVersion=1.0.0-SNAPSHOT                     
