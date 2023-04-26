pipeline {
  agent any
  stages {
    stage('test01') {
      steps {
        echo 'Ni tebe kinca-mylca'
        retry(count: 3)
      }
    }

    stage('build') {
      steps {
        bat(script: 'cd c:\\test', returnStatus: true)
      }
    }

    stage('test02') {
      steps {
        powershell 'asdadada.ps1'
      }
    }

  }
}