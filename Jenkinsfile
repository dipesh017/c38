pipeline {
  agent any
  stages {
    stage('Build Stage') {
      steps {
        sh '''cd vote
docker build .
docker push'''
      }
    }

    stage('Deploy Stage') {
      steps {
        sh '''ECR Commands
wxbw
wbjdx'''
      }
    }

  }
  environment {
    ECS_CLUSTER = 'vote-app'
    ENVIRONMENT = 'global'
  }
}