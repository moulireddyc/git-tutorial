pipeline {
  agent any
  stages {
    stage('PULL SCM') {
      steps {
        bat 'echo "Welcome to Blue Ocean for pipe line creation"'
      }
    }

    stage('Script run') {
      steps {
        sh '''echo "Print server uptime"
wmic path Win32_OperatingSystem get LastBootUpTime'''
      }
    }

  }
}