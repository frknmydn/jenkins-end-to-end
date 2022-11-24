pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    
                    git branch: 'main', url: 'https://github.com/frknmydn/jenkins-end-to-end.git'
                }
            }
        }
       
    }
}
        
