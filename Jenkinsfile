pipeline{
agent any
stages
{
stage('clone')
{
steps{
git 'https://github.com/Manoj05M5/Devoops.git'
}
}
stage('build')
{
steps{
sh 'javac hello.java'
}
}
stage('run')
{
steps
{
sh 'java hello'
}
}
}
}
