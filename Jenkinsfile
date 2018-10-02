pipeline {
    agent any

    tools {
        maven 'localMaven'
    }

    stages{
        stage("Build"){
            staps{
                sh 'mvn clean package'
            }
        }
    }
}