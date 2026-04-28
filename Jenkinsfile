pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project using Maven...'
                bat 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'mvn test'
            }
        }
    }
}
