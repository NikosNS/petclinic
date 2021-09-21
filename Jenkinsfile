pipeline {
  agent any
  
  stages {
    stage('Built Assets') {
      agent any
      steps {
        echo 'Building Assets...'
      }
    }
    stage('Test') {
      agent any
      steps {
        echo 'Testing stuff...'
      }
    }
    stage('Test2') {
      agent any
      steps {
        sh 'cat /etc/hosts'
     }
   }
  }
}
