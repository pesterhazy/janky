pipeline {

  agent any
  options {
  }

  environment {
    CI = 'true'
  }
  tools { nodejs "NodeJS Latest" }

  stages {

    stage('Hello worlding') {
      steps {
        sh 'echo hello world'
      }
    }

  }
}
