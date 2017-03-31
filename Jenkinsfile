pipeline {
  agent any
  stages {
    stage('Commit hook') {
      steps {
        echo 'Success'
      }
    }
    stage('Build Branch Docker Image') {
      steps {
        echo 'Success'
      }
    }
    stage('Run Branch Docker Image Tests - Feature Flag OFF') {
      steps {
        parallel(
          "Run Branch FVT Tests": {
            echo 'Success'
            
          },
          "Run Branch Unit Tests": {
            echo 'Success'
            
          },
          "Report Branch Code Coverage": {
            echo 'Success'
            
          }
        )
      }
    }
    stage('Run Branch Docker Image Tests - Feature Flag ON') {
      steps {
        parallel(
          "Run Branch FVT Tests": {
            echo 'Success'
            
          },
          "Run Branch Unit Tests": {
            echo 'Success'
            
          },
          "Report Branch Code Coverage": {
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
