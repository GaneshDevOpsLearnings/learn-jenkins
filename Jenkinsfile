pipeline{
    agent {
        lable 'workstation'
    }
    stages{
        stage('test 1'){
            steps{
                echo 'this is from test 1 stage'
            }
        }
    }
    post{
        always{
            echo 'sending an email'
        }
    }
}