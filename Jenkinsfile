pipeline{
    agent any
    stages{
        stage('Checkout the Server'){
            steps{
                git 'https://github.com/victorsh01/spring-petclinic-rest.git'
            }
        }
        stage('Build and Run the Server'){
            steps{
                sh "mvn spring-boot:run"
            }
        }
    }
}
