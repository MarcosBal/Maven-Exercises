pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Start'
        sh 'git checkout answer3'
        sh 'mvn clean install -Dlicense.skip=true'
        echo 'Build Complete'
      }
    }

  }
}