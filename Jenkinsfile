pipeline {
  agent any
  stages {
    stage('start') {
      steps {
        echo 'step 1'
      }
    }
    stage('wait') {
      steps {
        sleep 10
      }
    }
    stage('ram tam tam') {
      steps {
        sh 'echo "ram tam tam"'
      }
    }


    stage('end') {
          steps {
            sh 'echo "ram tam tam - end"'
          }
    }
  }
}