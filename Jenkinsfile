pipeline{
    agent any
    stages{
        stage("Code Deployment")
        {
            steps{
                
                
                sh 'scp -r /tmp/node-app-inst root@AnsibleServer:/tmp'
        
            }
        }
    }
}
