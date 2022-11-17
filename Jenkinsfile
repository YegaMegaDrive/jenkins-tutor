pipeline {
    agent any
    tools{
     maven "any"
    }
        stages {
            stage('build') {
                steps {
                    sh 'mvn --version'
                }
            }
        }
}