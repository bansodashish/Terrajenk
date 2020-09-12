pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Stage'
        sh 'jenkins/build.sh'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing stage'
        sh 'jenkins/test.sh'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy stage'
        sh 'jenkins/deploy.sh'
      }
    }

  }
}