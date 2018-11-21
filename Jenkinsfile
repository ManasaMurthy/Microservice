#!groovy
node{
  
  sh 'git show'
  office365ConnectorSend message: "Hello world", webhookUrl: "${env.HOOK}"
}
