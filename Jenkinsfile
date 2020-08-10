pipeline{
    agent any
    stages{
        stage("Code Deployment")
        {
            steps{
                sh 'cd /home/ansible'
                sh 'pwd'
                sh 'ansible-playbook /home/ansible/playbook.yml'
                
        
            }
        }
    }
}
