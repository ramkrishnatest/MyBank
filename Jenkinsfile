pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'Hello World'
      }
    }

    stage('Clone') {
      steps {
        git(url: 'https://github.com/ramkrishnatest/TCS.git', branch: 'main')
      }
    }

  }
}