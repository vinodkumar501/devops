pipeline {

  agent any 

  stages {
		
      stage (“build”)	{
		  	
          steps {
				
               sh ‘yum update -y’
				
               sh "echo ‘building an application’"
			
             }
		
          }
        
      stage (“testingg”)	{
		
          steps {
				
		sh "echo ‘testing an application’"
			
             }
		
          }
		
      stage (“deploy”)	{
		
          steps {
						
              sh "echo ‘deploying an application’"
			
             }
		
          }
	
     }

  }	
