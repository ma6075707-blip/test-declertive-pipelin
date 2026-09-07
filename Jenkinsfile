pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'medo'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'running'
          }
        }

        stage('test 2') {
          steps {
            echo 'running test 2'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }

  }
}