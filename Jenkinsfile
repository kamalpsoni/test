pipeline {
  agent any
  stages {
    stage('Git checkout testing1234') {
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
