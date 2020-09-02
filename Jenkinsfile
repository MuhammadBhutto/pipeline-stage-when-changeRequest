pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			//when{	changeRequest title:"when-pr"	}
		           when { changeRequest () }
		
            steps {                
                echo 'Hello World changing request'
            }
        }
    }
}
