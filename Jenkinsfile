#!groovy
node{
  
  git show -s 
  office365ConnectorSend message: "Hello world", webhookUrl: "${env.HOOK}"
}
