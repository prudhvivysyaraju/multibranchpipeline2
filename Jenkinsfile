pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s31bucket --template-body file://simples3bucket.json --region 'ap-southeast-2'"
              }
             }
            }
            }
