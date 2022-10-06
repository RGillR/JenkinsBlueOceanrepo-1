pipeline {
   agent any
   
   environment {
       DEMO='1.3'
   }

   stages {
      stage('stage-1') {
         steps {
            echo "This is build number $BUILD_NUMBER of demo $DEMO"
            sh '''
               echo "Using a multi-line shell step in side echo for test file"
               chmod +x test.sh
               ./test.sh

               echo "now in notest file"
               chmod +x notest.sh
               ./notest.sh
            '''
         }
      }
   }
}