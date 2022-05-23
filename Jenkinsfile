pipeline {
 
agent any 


stages {

    stage('SCM'){
        steps{
          echo "git pull my code step1"
	}
    }
    stage('Deploy'){
      steps{
         echo "deplying my code"       
   
      }
  
    }
    stage('Test'){
      steps{
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
