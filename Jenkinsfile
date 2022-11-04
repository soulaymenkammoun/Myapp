pipeline{
    agent any
    stages{
       stage('GetCode'){
            steps{
                git branch: 'master',
                url : 'https://github.com/soulaymenkammoun/Myapp.git'
            }
       }
    }
}
