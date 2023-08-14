pipeline
{
 agent any
 stages{
  stage('Build Application'){
 bat 'mvn clean install'
 }
 
 
  stage('Deploy Application to MuleSoft CloudHub'){
  bat 'mvn cleaSn deploy -DmuleDeploy'
  }
 
 
}
}