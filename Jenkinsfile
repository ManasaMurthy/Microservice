#!groovy

stage 'Dev Build'
node {
    try{
        checkout scm
        mvn 'clean compile'
    }catch(Exception e){
        
    }
}

stage 'Unit Testing'
node {
    try{
         mvn 'test'
    }catch(Exception e){
        
    }
   
}

stage 'Static Code Analysis - Sonar'
node {
    try{
        
    }catch(Exception e){
       
    }
   
}

input message: "Ready for Dev Deployment?"

stage name: 'Dev Deployment', concurrency: 1
node {
   echo 'deploying..'
}

