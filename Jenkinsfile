pipeline
{
agent any
stages
{
stage("Preconfig Setup")
{
steps
{
script
{
git credentialsId: 'pdaram8@gmail.com', url: 'https://github.com/kumardaram76/Pipeline-Jenkins.git'
}
}
}
stage("maven clean ")
{
steps
{
script
  
{
sh label: '', script: 'mvn clean'
}
}
}
stage("maven install")
{
steps
{
script
{
sh label: '', script: 'mvn install'

}
}
}
stage("MAven PACKAGE")
{
steps
{
script
{
sh label: '', script: 'mvn package'
}
}
}
stage("Veracode")
{
steps
{
script
{
echo 'Hello World'
}
}
}
stage("Docker Build")
{
steps
{
script
{
echo 'Hello World'
}
}
}
stage("Docker Push")
{
steps
{
script
{
echo 'Hello World'
}
}
}
stage("Cleanup")
{
steps
{
script
{
echo 'Hello World'
}
}
}
}
}
