pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Start'
        sh 'mvn clean install -Dlicense.skip=true'
        echo 'Build Complete'
      }
    }

  }
}