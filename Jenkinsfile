pipeline {
 
agent any 


stages {

    stage('SCM'){
        steps{
          echo "git pull my code step1"
	}
    }
    stage('Deploy'){
      step{
         echo "deplying my code"       
   
      }
  
    }
    stage('Test'){
      step{
        echo " testing my code finall"
      }
    }

    stage('deploy test'){
      steps{
         echo "deploying testing"
      }
    }



}

}
