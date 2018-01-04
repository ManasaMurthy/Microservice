#!groovy

stage 'Build'
node {
    try{
        if(${env.REPO_TYPE} == 'micro'){
         echo "micro"            
        } else {
           echo "spark"   
        }
    }catch(Exception e){
        
    }
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
