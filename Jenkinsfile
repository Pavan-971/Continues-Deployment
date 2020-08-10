pipeline{
    agent any
    stages{
        stage("Code Deployment")
        {
            steps{
                
                sh 'ansible-playbook /home/ansible/playbook.yml'
        
            }
        }
    }
}
