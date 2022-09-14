pipeline {
  
  agent any
  
  stages {
        stage('Build') {
  
          steps {
                 echo "Hello World"'
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
