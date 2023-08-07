pipeline {
  agent any
  stages {
    stage('stage 1') {
      parallel {
        stage('stage 1') {
          steps {
            echo 'test1'
            echo 'test2'
          }
        }

        stage('stage 2') {
          steps {
            echo 'test1 stage 2'
          }
        }

      }
    }

    stage('finish') {
      steps {
        echo 'finish'
      }
    }

  }
}