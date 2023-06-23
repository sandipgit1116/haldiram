Pipeline {
  agent any
  Stages {
    stage ('checkout') {
      step {
        checkout scm
      }}
    steps {
      sh ' /home/sandip/Documents/devops-tools/apache-maven-3.9.0/bin/mvn install '
    }}
  stage ('Deployment') {
    steps {
      sh ' cp target/haldiram.war /home/sandip/Documents/devops-tools/apache-tomcat/webapps '
    }
  }}}
