pipeline {
  agent any
  stages {
    stage('Stage-1') {
      steps {
        echo 'step 1 of stage 1'
      }
    }

    stage('stage-3') {
      steps {
        echo 'stage-3'
        sh './test.sh'
      }
    }

  }
}