pipeline {
  agent any 
  environment {
    DEPLOY_TO = 'production'
  }
  stages {
    stage ("when-ex") {
      when {
        environment name: 'DEPLOY_TO' , value: 'production'
      }
      steps {
        echo "deploy to jenkins"
      }
    }
  }
}
