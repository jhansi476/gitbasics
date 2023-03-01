pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'application is developed'
            }
        }
        stage('Testing') {
            steps {
                echo 'automation testing'
            }
        }stage('UAT') {
            steps {
                echo 'waiting for UAT'
            }
        }
        stage('release') {
            steps {
                echo 'app is ready to release to produce servers'
            }
        }
    }
}
