pipeline {
    agent any
    tools{
     ant 'apache-ant-1.9.9'   
     jdk 'java8'   
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'build'
                archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true
                
            }
            }
        }
}
