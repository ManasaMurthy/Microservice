#!groovy
node{
  
  sh 'git init'
 sh 'git show'
  office365ConnectorSend message: "Hello world", webhookUrl: "${env.HOOK}"
}
