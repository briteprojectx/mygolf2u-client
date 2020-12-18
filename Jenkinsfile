pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/briteprojectx/mygolf2u-client.git', branch: '/master', credentialsId: 'britesoftgit', poll: true)
      }
    }

  }
}