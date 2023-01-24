pipeline {
     agent any
    tools { 
        maven 'Maven' 
        jdk 'Java' 
    }
    stages {
        stage('Build') { 
            steps {
                bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}


