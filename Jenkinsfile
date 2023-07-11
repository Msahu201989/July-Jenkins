pipeline {

 agent {
    node { label 'Workstation' }
 }

 stages {

  stage ('code quality') {
    steps {
     echo 'code quality'
    }
  }

   post {
        always {
            echo 'I will always say Hello again!'
        }
    }
}