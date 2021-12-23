node{
    stage('SCM Checkout'){
	 git 'https://github.com/likithreddysiddala/maven-code'
	 }
	 stage('Compile-Package'){
	 //Get maven home path 
	 def mvnHome = tool name: 'maven-3', type: 'maven'
	 sh "{mvnHome}/opt/apache-maven-3.8.4/mvn package"
	 }
	 
    }
