pipeline {
    agent any
    stage("SCM Checkout"){
         steps{
               echo "Cloning Repositroy from Git Hub................"
               git 'https://github.com/bharavi14/mavenProject2.git'
         }   
    }
    stages {
        stage('MVN Build') {
             steps{
                 echo "Building Jar File.........."
                sh "mvn clean install"
            }
        }
    }
}
