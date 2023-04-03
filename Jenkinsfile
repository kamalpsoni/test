pipeline {
  agent any
  stages {
    stage('Git checkout testing12') {
      steps {
        sh 'kubectl get node'
      }
    }
    stage('Helm command') {
      steps {
        sh 'helm list'
      }
    }

  }
}
