pipeline {
  agent any
  stages {
    stage('Stage-1') {
      parallel {
        stage('Stage-1') {
          steps {
            echo 'step 1 of stage 1'
          }
        }

        stage('stage-2') {
          steps {
            echo 'parallel stage to stage-1'
          }
        }

      }
    }

    stage('stage-3') {
      steps {
        echo 'stage-3'
      }
    }

  }
}