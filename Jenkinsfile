pipeline {
    agent any
    
    stages {
        stage("Checkout") {
            when {
                branch 'git' // Replace 'git' with actual branch name like 'main' or 'master'
            }
            steps {
                git url: 'https://github.com/Esthersurya1223/Calculator-houari.git'
            }
        }
        
        stage("Maven Build") {
            when {
                branch 'maven' // Replace 'maven' with the actual branch name
            }
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
