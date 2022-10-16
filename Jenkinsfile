pipeline {
agent any

stages {
    stage ('Build') {
      steps {
          echo 'Build'
    }
}
stages {
    stage ('Test') {
      steps {
          echo 'Build'
    }
}
stages {
    stage ('Sonarqube') {
      steps {
          echo 'Build'
    }
}
stage ('Push to artifactory') {
    steps {
        echo push artifactory
    }
}
post {
    Failure {
        echo 'failed'
    }
    Success {
        echo 'Success'
    }
    alway {
        echo 'always'
    }
}