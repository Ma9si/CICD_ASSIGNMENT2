pipeline{
    agent any
    stages{
        stage('Clean'){
            steps{
                echo "Clean Stage"
                sh "mvn clean"
            }
        }
        stage('Test'){
            steps{
                echo "Test Stage"
                sh "mvn test"
            }
        }
        stage('Package'){
            steps{
                echo "Package Stage"
                sh "mvn package"
            }
        }
        stage('install'){
            steps{
                echo "install Stage"
                sh "mvn install"
            }
        }
        
    }
}
