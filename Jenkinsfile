pipeline {
    agent {
        label 'SLAVE_1'
    }
    stages {
        stage ('stage_A') {
            steps {
                echo "This is the first stage"
            }
        stage ('stage_B') {
            steps {
                echo "This is the second stage"
            }
        }
    }
}
