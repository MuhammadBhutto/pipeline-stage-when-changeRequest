pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			//when{	changeRequest title:"when-pr"	}
		when { changeRequest authorEmail: "muhammad.bhutto@gmail.com" }
		
            steps {                
                echo 'Hello World changing request'
            }
        }
    }
}
