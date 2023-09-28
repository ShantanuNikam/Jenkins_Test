pipeline {
  agent {
    node {
      label 'Git'
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