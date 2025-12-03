pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hi blal'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'bebo'
          }
        }

        stage('test 1') {
          steps {
            echo 'blal'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'hiiiiiiiiiiii'
      }
    }

  }
}