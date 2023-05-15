@Library('Jenkins_Share_lib') _

pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    branch: "main",
                    url: 'https://github.com/Prathm6601/DevSecOps-java.git'
                }
            }
        }
    }
}
