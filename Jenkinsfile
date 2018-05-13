node ("linux") {
    stage ("GetInstances") {

        sh "aws ec2 describe-instances --region us-east-1"
     }
    stage("RunINstances" {
        sh "aws ec2 run-instances --image-id ami-467ca739 --count 1 --instance-type t2.micro --key-name MeeraKeyPair --security-group-ids sg-5e916829 --subnet-id subnet-83a4ccde --region us-east-1"
     }
 }
