pipeline {
    agent any
    tools{
        maven 'Maven3_8_6'
    }
    stages {
        stage('Build') {
            steps {
                dir("Curso-Microservicios/"){
                    sh "mvn clean package"
                }
            }
        }
    }
}