pipeline {
    agent any
    tools{
     maven "maven"
    }
        stages {
            stage('build') {
                steps {
                    sh 'mvn clean compile install'
                }
            }
         stage('run'){
            steps {
                sh 'chmod +x mvnw && nohup ./mvnw spring-boot:run -Dserver.port=8989 '
            }
         }
        }
}