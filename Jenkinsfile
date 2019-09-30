node{
   satge('scm checkout'){
    git "https://github.com/jenkins-docs/simple-java-maven-app"
	}
   satge('compile-package'){
   def mvnHome =tool name:'maven 3', type: 'maven'
   sh"${mvnHome}/bin/mvn package"
   }
}
