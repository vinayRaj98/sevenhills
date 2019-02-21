node{
    stage('SCM Checkout'){
        git 'https://github.com/vinayRaj98/sevenhills'
    }
    stage('Compile-Package'){
       def mvnHome = tool name: 'maven', type: 'maven' 
       sh "mvn clean package"
        }
    }
