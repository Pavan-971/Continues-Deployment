pipeline{
    agent any
    stages{
        stage("Code Deployment")
        {
            steps{
                
                sh 'rm -rf /tmp/node-app-inst'
                sh 'scp -r /tmp/node-app-inst root@AnsibleServer:/tmp'
        
            }
        }
    }
}
