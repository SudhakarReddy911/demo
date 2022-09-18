pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo docker build'
      }
    }

    stage('Linux test') {
      steps {
        sh 'echo linux test'
      }
    }

  }
  environment {
    EC2_ACCESS = 'ECS'
  }
}