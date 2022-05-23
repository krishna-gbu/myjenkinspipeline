pipeline {
 
agent any 


stages {

    stage('SCM'){
        steps{
          echo "git pull my code step1"
	  git 'https://github.com/krishna-gbu/simple-java-maven-app.git'
	}
    }
    stage('Build'){
      steps{
         echo "building my code" 
	 sh 'mvn clean package'
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
