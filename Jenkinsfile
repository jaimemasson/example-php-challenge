pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building...'
        git(url: 'git@github.com:jaimemasson/example-php-challenge.git', branch: 'master', poll: true)
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing...'
      }
    }
  }
}