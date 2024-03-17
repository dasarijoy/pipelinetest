pipeline {
  agent any
  environment {
    course ="jenkins"
    name = "Dileep"
  }
  stages {
    stage('env-stage') {
      environment {
        cloud = "GCP"
      }
      steps {
        echo "welcome to ${name}"
        echo "your enrolled for ${course} course"
        echo "your certified in ${cloud} "
      }
    }
    stage ('second-stage') {
      steps {
        echo "welcome to ${name}"
        echo "your enroled for ${course} course"
        echo "your certified on ${cloud} course"
      }
    }
  }
}
