pipeline {
  agent any
  stages {
    stage('install') {
      parallel {
        stage('install') {
          steps {
            sh 'sudo yum install -y dhcp'
          }
        }

        stage('mkdir') {
          steps {
            sh 'sudo mkdir test'
          }
        }

      }
    }

  }
}