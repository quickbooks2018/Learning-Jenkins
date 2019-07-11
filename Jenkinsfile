node {
 stage('SCM Checkout') {
   git 'https://github.com/quickbooks2018/Learning-Jenkins'
 }
 stage('Compile-Package') {
 //Get Maven Home Path
   def mvnHome = tool name: 'maven3', type: 'maven'
  sh "${mvnHome}/opt/maven/bin/"
 }
}
