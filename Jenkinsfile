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
                sh 'ls'
                echo 'Yarn Install1'
                echo '******************************'
            }
        }

        stage('Yarn Build') {
            steps {
                echo 'Yarn Build1'
                echo '******************************'
            }
        }


        stage('Deploy') {
            steps{
                sh 'git add .'
                sh 'git commit -m testCommit'
                sh 'git push origin main'
                echo 'Deploy1'
                echo '******************************'
            }
        }
    }
}
