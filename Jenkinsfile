pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh ant -Dbuild=build/classes bundle
                
                
            }
            }
        }
}
