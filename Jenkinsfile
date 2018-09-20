pipeline {
  agent any

  stages {
    stage('stage 1') {
      steps {
        echo 'step 1'
        echo 'step 2'
      }
    }
    stage('stage 2') {
      steps {
        step('s2.1') {
            sleep 10
        }
        step('s2.2') {
            sleep 10
        }
      }
    }
    stage('stage 3') {
      steps {
        sh 'echo "ram tam tam"'
      }
    }


    stage('stage 4') {
          steps {
            sh 'echo "ram tam tam - end"'
          }
    }
  }
}