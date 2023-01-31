pipeline {
    agent any

    stages {        
          stage('Build') {
            steps {
                echo 'Build'
                sh "mvn package"
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
                sh "mvn Test"
            }
        }
        
        stage('Deploy Dev') {
            steps {
                echo 'Deploy Dev'
            }
        }
        stage('Deploy Test') {
            steps {
                echo 'Deploy Test'
            }
        }
    }
}



















