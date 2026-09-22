pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'Building ....'
        sh 'chmod +x ./hello.sh' 
        sh './hello.sh'
      }
    }
  }
}
