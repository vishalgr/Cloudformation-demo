pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2Instance --template-body file://ec2.yml --region 'us-west-2'"
              }
             }
            }
            }