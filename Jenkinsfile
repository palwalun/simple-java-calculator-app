pipeline{
 agent any
  parameters{ 
     choice(
	  name: 'ENV', choices: ['QA', 'PROD'], description: 'Select Environment'
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