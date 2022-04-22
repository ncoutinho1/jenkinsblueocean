pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build stage'
          }
        }

        stage('Parallel') {
          steps {
            echo 'Paralle Build'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Testing'
      }
    }

    stage('Deply') {
      steps {
        echo 'Deploying'
      }
    }

  }
}