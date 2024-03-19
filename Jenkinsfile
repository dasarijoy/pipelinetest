pipeline {
  agent any 
  environment {
    DEPLOY_TO = 'productions'
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
