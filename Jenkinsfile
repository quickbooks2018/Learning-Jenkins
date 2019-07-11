node {
 stage('SCM Checkout') {
   git 'https://github.com/quickbooks2018/Learning-Jenkins'
 }
 stage('Compile-Package') {
 //Get Maven Home Path
  // def mvnHome = tool name: 'maven3', type: 'maven'
  def mvn = tool (name: 'maven3', type: 'maven') + '/bin/mvn' 
  sh "${mvn} clean package deploy"
 }
}
