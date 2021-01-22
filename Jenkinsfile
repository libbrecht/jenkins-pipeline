pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'etape de build'
            sh '''
cd /TP3/jenkins-pipeline


'''
          }
        }

        stage('Python') {
          steps {
            sh 'python --version'
          }
        }

      }
    }

    stage('test') {
      steps {
        echo 'etape de test'
      }
    }

    stage('deploy') {
      steps {
        echo 'etape de deploiement'
      }
    }

  }
}