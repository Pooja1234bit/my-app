pipeline{
agent any
tools {
  maven 'MAVEN_HOME'
}
stages{
stage("Build"){
steps{
sh script: 'mvn clean package'}
}
}
}