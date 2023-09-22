pipeline {
    agent any 
    stages {
        stage('Deploy') { 
            steps {
                echo 'deployeing fucker'
                dir('/var/www/JenkinsDemo'){
                    git 'pull'
                    sh 'service nginx restart'
                }
                echo 'deployed'
            }
        }
    }
}
