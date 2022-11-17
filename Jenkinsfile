pipeline {
    agent any
    tools{
     maven "3.8.6"
    }
        stages {
            stage('build') {
                steps {
                    sh 'mvn --version'
                }
            }
        }
}