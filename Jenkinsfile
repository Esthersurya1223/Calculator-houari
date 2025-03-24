pipeline {
    agent any
    
    stages {
        stage("checkout"){
            when {
                branch "git"
            }
            steps {
                https://github.com/Esthersurya1223/Calculator-houari.git
                
            }
        }
        stage("maven"){
            when {
                branch "maven"
            }
            steps {
                
                sh 'mvn clean package'
                
            }
        }
    }
}
