pipeline {
    agent {
        label 'slave1'
    }
    stages {
        stage('Hello') {
            steps {
                sh '''
                    echo "Hello india"
                    echo "hello rishi"
                    mkdir rushi
                    cd rushi
                    echo "Now inside rushi directory"
                '''
            }
        }
    }
}
