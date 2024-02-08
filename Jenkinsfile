pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
        stage('test') {
            steps {
                echo 'Test stage running.....'
            }
        }
        stage('deploy') {
            steps {
                echo 'Deployment stage running.....'
            }
        }
    }
}