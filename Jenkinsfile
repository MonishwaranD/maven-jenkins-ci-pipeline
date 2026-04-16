pipeline {
    agent any

    tools {
        maven 'Maven'
        jdk 'JDK17'
    }

    stages {
        stage('Build and Test') {
            steps {
                bat 'mvn clean test'
            }
        }
    }
}
