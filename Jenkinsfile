pipeline {
    agent any
    environment {
        PATH = "/usr/local/apache-maven/apache-maven-3.8.6/apache-maven-3.8.6/bin:$PATH"
    }
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
        stage('Sonar-qube') {
            steps {
                echo 'Sonar-qube'      
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



















