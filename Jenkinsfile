pipeline {
    agent {
        label 'SLAVE_1'
    }
    stages{
        stage ('stage_A'){
            steps{
                sh 'sleep 5'
                echo "This is the first stage"
            }
        }
    }
}
