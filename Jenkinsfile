pipeline {
    agent any
    environment {
        PATH = "C:\\Program Files\\apache-maven-3.9.9\\bin;${env.PATH}"
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
