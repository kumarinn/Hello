pipeline {
  agent any
  stages {
    stage('Build') {
    steps {
    bat label: '', script: 'java -version'
    }
    }
    stage('Test') {
    steps {
    input 'Do you want to continue?'
    }
    }
    stage('Release') {
    steps {
    echo 'This is the end of the pipeline!!!!!!!!!!!!!!!!!!!!!!!!!!!!'
    }
    }
    }
    }
