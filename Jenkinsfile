pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        retry(count: 1)
        echo 'Hello World'
      }
    }

  }
  environment {
    demo = '1'
  }
}