pipeline{
    agent any
    stages{
        stage("Code Deployment")
        {
            steps{
               
                
                
                sh 'tar -zcvf /home/tmp.tar.gz /tmp  '
               
                sh "sshpass -p 'pavankumar' scp /tmp/tmp.tar.gz root@18.220.35.224:/tmp"
                sh 'ansible-playbook /home/ansible/playbook.yml'
                sh 'echo ok'
                
                 


                
        
            }
        }
    }
}
