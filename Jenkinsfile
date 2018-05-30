pipeline {
 agent {
        docker { image 'node:7-alpine' }
  }
      stage('Build') {
        sh 'echo Build'
      }
      stage('Test') {
          sh 'echo Test'
      }
      stage('Infra Creation') {
          sh 'echo Infra Creation'
      }
      stage('Deploy') {
          sh 'echo Deploy'
      }
}
