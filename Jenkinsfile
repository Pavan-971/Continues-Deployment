pipeline{
    agent any
    stages{
        stage("Code Deployment")
        {
            steps{
               
                
                sh 'sudo chmod 777 /tmp'
                sh 'tar -zcvf /tmp/tmp.tar.gz /tmp  '
                sh 'sudo chmod 777 /tmp/tmp.tar.gz'
                sh "sshpass -p 'pavankumar' scp /tmp/tmp.tar.gz root@18.220.35.224:/tmp"
                sh 'ansible-playbook /home/ansible/playbook.yml'
                sh 'echo ok'
                
                 


                
        
            }
        }
    }
}
