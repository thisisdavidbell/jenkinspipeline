pipeline {
  agent any
  stages {
    stage('Build docker image 1') {
      steps {
        parallel(
          "Build docker image 1": {
            echo 'Success'
            
          },
          "Build docker image 2": {
            echo 'Success'
            
          }
        )
      }
    }
  }
}