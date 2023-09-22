pipeline {
    agent any 
    stages {
        stage('Deploy') { 
            steps {
                echo 'deployeing fucker'
                dir('/var/www/JenkinsDemo'){
                    sh 'sudo git pull origin master'
                    sh 'sudo service nginx restart'
                }
                echo 'deployed'
            }
        }
    }
}
