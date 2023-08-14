pipeline
{
 agent any
 stages{
  stage('Build Application'){
 bat 'mvn clean install'
 }
 
 
  stage('Deploy Application to MuleSoft CloudHub'){
  bat 'mvn clean deploy -DmuleDeploy'
  }
 
}
}