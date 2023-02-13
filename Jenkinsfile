pipeline {
    agent any
    stages {
        stage('MVN Build') {
             steps{
                 echo "Building Jar File.........."
                sh "mvn clean install"
            }
        }
    }
}
