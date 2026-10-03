pipeline{
    agent { label 'linux'}
    
    stages{
        stage('checkout')
        {
            steps{
                git branch: '*/main',
                url :"https://github.com/skarzu05-glitch/jenkins-practise.git"
            }
        }
       stage('Run Script'){
           steps{
               sh  'sh hello.sh'
           }
       }
    }
    
    
}
