pipeline {
  
  agent any
  
  stages {
        stage('Build') {
  
          steps {
                 sh 'echo "Hello World"'
            }
        }
        stage('test') {
  
          steps {
                 sh "make test" 
            }
        }
        stage('Deploy') {
  
          steps {
                 sh "make deploy" 
            }
        }
      
  }
}
