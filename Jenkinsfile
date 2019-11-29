pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Hello '
        git(url: 'https://github.com/heenakousarr/AzureDevOps', branch: 'master')
      }
    }
  }
}