pipeline {
  agent any
  stages {
    stage('Commit hook') {
      steps {
        echo 'Success'
      }
    }
    stage('Build Docker Image') {
      steps {
        echo 'Success'
      }
    }
    stage('Run Docker Image Tests') {
      steps {
        parallel(
          "Run FVT Tests": {
            echo 'Success'
            
          },
          "Run Unit Tests": {
            echo 'Success'
            
          },
          "Report Code Coverage": {
            echo 'Success'
            
          }
        )
      }
    }
    stage('Compose Component') {
      steps {
        echo 'Success'
      }
    }
    stage('Run Component Tests') {
      steps {
        echo 'Success'
      }
    }
    stage('Compose MQoC') {
      steps {
        echo 'Success'
      }
    }
    stage('Run Product BVT') {
      steps {
        echo 'Success'
      }
    }
  }
}