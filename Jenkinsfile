pipeline {
  
  agent any
  
  stages {
        stage('Build') {
  
          steps {
                { sh 'make build' }
            }
        }
        stage('test') {
  
          steps {
                { sh 'make test' }
            }
        }
        stage('Deploy') {
  
          steps {
                { sh 'make deploy' }
            }
        }
      
  }
}
