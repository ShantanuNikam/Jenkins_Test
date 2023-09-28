pipeline {
  agent {
    node {
      label 'Start_Pipeline'
    }

  }
  stages {
    stage('Pull from Git') {
      steps {
        git(url: 'https://github.com/ShantanuNikam/Jenkins_Test.git', branch: 'master', changelog: true)
      }
    }

  }
}