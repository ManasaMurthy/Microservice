#!groovy
node{
  
echo "${GIT_BRANCH}"
  office365ConnectorSend message: "Hello world", webhookUrl: "${env.HOOK}"
}
