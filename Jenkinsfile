pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/aviazo/hello-world-python.git', branch: 'master', credentialsId: 'github')
      }
    }

    stage('build') {
      steps {
        echo 'hellow from build'
      }
    }

    stage('test') {
      steps {
        echo 'hellow from test'
      }
    }

    stage('package') {
      steps {
        echo 'hellow from package'
      }
    }

  }
}