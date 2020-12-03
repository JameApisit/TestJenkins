pipeline {
    
    agent any  

    stages {

        stage('Init'){
            steps {
                echo 'Init1'
                echo '******************************'
            }
        }

        stage('Yarn Install') {
            steps {
                echo 'Yarn Install1'
                echo '******************************'
            }
        }

        stage('Yarn Build1') {
            steps {
                sh 'ls'
                echo 'Yarn Build'
                echo '******************************'
            }
        }


        stage('Deploy1') {
            steps{
                sh 'git add .'
                sh 'git commit -m testCommit'
                sh 'git push origin main'
                echo 'Deploy'
                echo '******************************'
            }
        }
    }
}
