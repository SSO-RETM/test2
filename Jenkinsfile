
pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                echo 'Start..'
            }
        }
        stage('Deploy') {
            steps {
                sh 'cat test2-file.txt'
                echo 'Deploy..'
            }
        }
        stage('End') {
            steps {
                echo 'End....'
            }
        }
    }
}
