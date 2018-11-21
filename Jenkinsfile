#!groovy
node{
  foo=$(git show --name-only)
  println foo
  office365ConnectorSend message: "Hello world", webhookUrl: "${env.HOOK}"
}
