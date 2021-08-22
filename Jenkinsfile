pipeline {
    agent any
	
	environment {
	  NAME='Sambasiva Rao' 
	  LASTNAME='Lagisetti'
	  }	
	  

    stages {
        stage('Build') {
            steps {
                echo 'First name: $NAME'
                echo ' Hello world'
              
                
            }
        }
        stage('Test') {
            steps {
                echo 'Last Name: $LASTNAME'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
