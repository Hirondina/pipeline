pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git 'https://github.com/Hirondina/pipeline.git'
      }
    }
    stage('Test') {
      steps {
        bat 'echo "Testing"'
      }
    }
    stage('Deploy') {
      steps {
        bat 'echo "Deploying"'
      }
    }
  }
}