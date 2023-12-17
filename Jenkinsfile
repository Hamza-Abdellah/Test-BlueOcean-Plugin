pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build completed'
      }
    }

    stage('Test Stages') {
      parallel {
        stage('Test1') {
          steps {
            echo 'Test1 completed'
          }
        }

        stage('Test2') {
          steps {
            echo 'Test2 Completed'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy completed'
      }
    }

  }
}