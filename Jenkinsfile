pipeline{
    agent any
    stages{
        stage("Code Deployment")
        {
            steps{
               
                sh 'ansible-playbook /home/ansible/playbook.yml'
                
                sh 'tar -zcvf /home/tmp.tar.gz /tmp  '
                sh 'chmod 777 /home/tmp.tar.gz'
                sh "sshpass -p 'pavankumar' scp /tmp/tmp.tar.gz root@18.220.35.224:/tmp"
                sh 'echo ok'
                
                 


                
        
            }
        }
    }
}
