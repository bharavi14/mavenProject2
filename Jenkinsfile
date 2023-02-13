pipeline {
    agent any
    stages {
        stage("SCM Checkout"){
            steps{
                echo "Cloning Repositroy from Git Hub................"
                git 'https://github.com/bharavi14/mavenProject2.git'
            }   
        }
        stage('MVN Build') {
             steps{
                 echo "Building Jar File.........."
                sh "mvn clean install"
            }
        }
    }
}
