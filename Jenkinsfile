pipeline{
agent any
stages{
stage('Clone'){
steps{
git url:'https://github.com/manasvi-a/simple-jenkins-demo.git',
branch:'main'
}
}
stage('Run script'){
steps{
sh 'chmod +x script.sh'
sh './script.sh'
}
}
}
}
