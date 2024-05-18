pipeline {
  agent any
  stages {
    stage('obacloud1') {
      steps {
        git(url: 'https://github.com/johntoby/DevCareerAssignment2.git', branch: 'main')
      }
    }

    stage('jenkins log') {
      steps {
        sh 'ls -la'
      }
    }

  }
}