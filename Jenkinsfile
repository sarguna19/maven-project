pipeline{
    agent any
    tools{
        maven 'localMAVEN'
    }
    stages {
      stage('Build'){
        steps {
            sh 'mvn clean package'
        }
      }
    }
}