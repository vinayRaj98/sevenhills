node{
    stage('SCM Checkout'){
        git 'https://github.com/vinayRaj98/wartest'
    }
    stage('Compile-Package'){
       def mvnHome = tool name: 'maven', type: 'maven' 
       sh "${mvnHome}/bin/mvn package"
        }
    }
