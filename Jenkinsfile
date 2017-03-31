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
    stage('Docker Image Tests - FF OFF') {
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
    stage('Docker Image Tests - FF ON') {
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
        parallel(
          "Feature Flag OFF": {
            echo 'Success'
            
          },
          "Feature Flag ON": {
            echo 'Success'
            
          }
        )
      }
    }
    stage('Compose MQoC') {
      steps {
        echo 'Success'
      }
    }
    stage('Run Product BVT') {
      steps {
        parallel(
          "Feature Flag OFF": {
            echo 'Success'
            
          },
          "Feature Flag ON": {
            echo 'Success'
            
          }
        )
      }
    }
    stage('Trigger Pull Request') {
      steps {
        echo 'Success'
      }
    }
  }
}
