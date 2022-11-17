pipeline {
    agent {
        docker {
            image 'maven:3.8.6-openjdk-11-slim'
            args '-p 8989:8989 -v $HOME/.m2:/root/.m2'
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