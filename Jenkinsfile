#!groovy
node{
  
  git show -s --pretty=%an
  office365ConnectorSend message: "Hello world", webhookUrl: "${env.HOOK}"
}
