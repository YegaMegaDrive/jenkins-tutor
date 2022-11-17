pipeline {
    agent {
        docker {
            image 'maven:3.8.6-openjdk-18'
            args '-p 8989:8989'
          }
           }
        stages {
            stage('build') {
                steps {
                    sh 'mvn --version'
                }
            }
        }
}