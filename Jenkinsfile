
pipeline {
  agent {
    docker { image 'node:19.8.1' }
  }
  stages {
    stage('Install') {
      steps { sh 'npm install' }
    }

    stage('Build') {
      steps { sh 'npm run-script build' }
    }
  }
}
