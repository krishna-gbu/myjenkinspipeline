pipeline {
 
agent any 


stages {

    stage('SCM'){
        steps{
          echo "git pull my code step1"
	  git 'https://github.com/krishna-gbu/simple-java-maven-app.git'
	  sh 'sudo yum install maven -y'
	}
    }
    stage('Build'){
      steps{
         echo "building my code" 
	 sh 'mvn clean package'
      }
  
    }
    stage('Deploy'){
      steps{
        echo " deploy my code finall"
	sh 'sudo yum install java -y'
	sh 'java -jar target/*.jar'
      }
    }

    stage('deploy test'){
      steps{
         echo "deploying testing"
      }
    }



}

}
