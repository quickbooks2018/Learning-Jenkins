node {
 stage('SCM Checkout'){
 git 'https://github.com/quickbooks2018/Learning-Jenkins'
 }
 stage('Compile-Package'){
  
  def mvnHome = tool name: 'M3', type: 'maven'
  sh "${mvnHome}/var/jenkins_home/tools/hudson.tasks.Maven_MavenInstallation/M3"
 }





}
