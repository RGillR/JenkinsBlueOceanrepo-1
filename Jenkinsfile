pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        echo "This is $BUILD_NUMBER of $DEMO"
        sh 'echo "This is Build_Number $BUILD_NUMBER and DEMo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}