pipeline {
  agent any
  stages {
    stage('ngnix') {
      steps {
        sh 'echo "this my ngix"'
      }
    }

    stage('navya') {
      parallel {
        stage('navya') {
          steps {
            sh 'echo "this is Navya"'
          }
        }

        stage('hari') {
          steps {
            sh 'echo "this is Hari friend"'
          }
        }

      }
    }

    stage('rajesh') {
      steps {
        sh 'echo "this is rajesh"'
      }
    }

  }
}