pipeline{
 agent any
  parameters{ 
     choice(
	  name: 'ENV', coices: ['QA', 'PROD'], description: 'Select Environment'
	 )
	}
   stages{
     stage('Checkout'){
	  steps{
	   checkout scm
	  }
	 }
   
   }

}