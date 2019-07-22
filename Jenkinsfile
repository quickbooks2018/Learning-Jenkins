node {
 stage('SCM Checkout'){
 git 'https://github.com/quickbooks2018/Learning-Jenkins'
 }
 stage('Compile-Package'){
  
  def mvnHome = tool name: 'M3', type: 'maven'
  sh "${mvnHome} package"
 }
 stage ('Email Notification'){
   mail bcc: '', body: 'Jenkins test', cc: '', from: '', replyTo: '', subject: 'Jenkins Job', to: 'alerts.cloudelligent@gmail.com'
  }





}
