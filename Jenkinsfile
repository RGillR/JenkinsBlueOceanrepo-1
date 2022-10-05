pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        echo 'This is $BUILD_NUMBER of $DEMO'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}