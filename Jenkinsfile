pipeline{
    agent any
    stages{
       stage('clone'){
        steps{
            git 'https://github.com/Banana1206/micro1.git'
        }
       }
        stage('gmail'){
        steps{
            emailext body: 'hahah', subject: 'jenkins annoucement', to: 'nguyentri120602@gmail.com'
        }
       }
    }
}