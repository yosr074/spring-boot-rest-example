pipeline {
  agent any
  
  stages {
  
    stage('Install dependencies') {
      steps {
        sh 'mvn clean install'
      }
    }
    stage('Run package jar') {
      steps {
        sh 'java -jar target/spring-boot-rest-example-0.5.0.jar'
       }
    }
  }
}
