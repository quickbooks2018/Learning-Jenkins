node {
 stage('SCM Checkout'){
 git 'https://github.com/quickbooks2018/Learning-Jenkins'
 }
 stage('Compile-Package'){
  
  def mvnHome = tool name: 'M3', type: 'maven'
  /bin/sh "${mvnHome}/usr/share/maven"
 }





}
