pipeline{
    agent any
    stages{
        stage("Code Deployment")
        {
            steps{
                sh ' rm -rf /tmp/node-app-inst'
                sh 'ansible-playbook /home/ansible/playbook.yml'
                sh 'sudo /tmp/node-app-inst/noderestart.sh'
                sh 'node /tmp/node-app-inst/Web-app/server.js'
                
        
            }
        }
    }
}
