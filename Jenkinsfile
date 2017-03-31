pipeline {
  agent any
  stages {
    stage('Build Docker Images') {
      steps {
        parallel(
          "Main Server": {
            echo 'Success'
            
          },
          "Web Front End": {
            echo 'Success'
            
          },
          "Database": {
            echo 'Success'
            
          }
        )
      }
    }
  }
}
