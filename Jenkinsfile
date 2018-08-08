pipeline {
  agent {
    node {
      label 'jdk8'
    }

  }
  stages {
    stage('Say Hello') {
      steps {
        echo "Hello ${My_NAME}!"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}