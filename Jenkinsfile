pipeline {
    agent any
    environment {
        PATH = "C:\\Users\\EBF3KOR\\Desktop\\apache-maven-3.9.9\\bin;${env.PATH}"
    }
    stages {
        stage('Check Maven Version') {
            steps {
                bat 'mvn -v'
            }
        }
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
