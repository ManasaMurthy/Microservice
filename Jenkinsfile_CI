#!groovy

node {
    try{
        checkout([$class: 'GitSCM', branches: [[name: '*/master']],
         doGenerateSubmoduleConfigurations: false,
         extensions: [], submoduleCfg: [],
         userRemoteConfigs: [[url: env.REPO_NAME]]])
         
        if(env.PROJECT_TYPE == 'micro'){
            echo "micro"
        } else {
           echo "spark"   
        }
    }catch(Exception e){
        
    }


stage 'Unit Testing'
node {
    try{
         echo 'test'
    }catch(Exception e){
        
    }
   
}

stage 'Static Code Analysis - Sonar'
node {
    try{
        
    }catch(Exception e){
       
    }
   
}
