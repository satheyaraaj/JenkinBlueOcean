pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo 'Stage 1'
      }
    }

    stage('Stage 2') {
      parallel {
        stage('Stage 2') {
          steps {
            echo 'Stage 2 Step'
          }
        }

        stage('Stage 2A') {
          steps {
            echo 'Stage 2A Steps'
          }
        }

      }
    }

    stage('Satage 3') {
      steps {
        echo 'Stage 3 step'
      }
    }

  }
}