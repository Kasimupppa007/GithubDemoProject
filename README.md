# GithubDemoProject
pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                echo 'Build process sucess..'
            }
        }
        stage('Test'){
            steps {
                echo 'Test the pocess sucess..' 
            }
        }
        stage('Deploy') {
            steps {
                echo'deploy the process sucess...' 
            }
        }
    }
}
