pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'Building ....'
        chmod +x ./hello.sh 
        sh './hello.sh'
      }
    }
  }
}
