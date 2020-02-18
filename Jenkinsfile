pipeline
{
agent any
tools {
  maven 'mav3n'
}
stages
{
stage('clean')
{
steps
{
sh script: 'mvn clean'
}
}
stage('Test and Package')
{
steps
{
sh script: 'mvn test package'
}
}
}
