pipeline {
  agent any
  environment {
    course ="jenkins"
    name = "Dileep"
  }
  stages {
    stage('env-stage') {
      environment {
      name = vanitha
      cloud = "GCP"
      }
      steps {
        echo "welcome ${name}"
        echo "you enrolled for ${course} course"
        echo "you are certified in ${cloud}"
      }
    } 
  }
}
