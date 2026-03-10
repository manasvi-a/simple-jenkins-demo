pipeline{
agent any
stages{
stage('Clone'){
steps{
git url:'',
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
