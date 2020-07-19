pipeline {
  agent: any
  stages {
    stage("Checkout-git") {
      steps {
        git poll: true, url: 'git@github.com:jesusmatiz/pipeline-jenkins.git'
      }
    }
    stage("SonarQube") {
      steps {
        echo "Ejecutando SonarQube"
      }
    }
    stage("Deploy") {
      steps {
        echo "Desplegando proyecto"
      }
    }
  }  
}