pipeline
{
 agent any
 stages{
  stage('Build Application'){
  
  steps{
  bat 'mvn clean install'
 }
 }
 
 
  stage('Deploy Application to MuleSoft CloudHub'){
  steps{
  bat 'mvn clean deploy -DmuleDeploy'
  }
  }
 
}
}