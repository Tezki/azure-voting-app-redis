pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            echo "$GIT_BRANCH"
         }
      }
      stage('Hello World') {
         steps {
            sh 'echo "Hello World"'
         }
      }
   }
}
