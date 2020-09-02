pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			//when{	changeRequest title:"when-pr"	}
		           when { changeRequest target: 'master' }
		
            steps {                
                echo 'Hello World changing request'
            }
        }
    }
}
