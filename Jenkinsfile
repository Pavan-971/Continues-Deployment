pipeline{
    agent any
    stages{
        stage("Code Deployment")
        {
            steps{
                
                sh 'rm -rf /tmp/*'
                sh 'scp -r /tmp root@AnsibleServer:/tmp'
        
            }
        }
    }
}
