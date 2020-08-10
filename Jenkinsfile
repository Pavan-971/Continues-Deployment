pipeline{
    agent any
    stages{
        stage("Code Deployment")
        {
            steps{
                
                sh 'ansible-playbook /home/ansible/playbook.yml'
                sh 'node /tmp/node-app-inst/Web-app/server.js'
                
        
            }
        }
    }
}
