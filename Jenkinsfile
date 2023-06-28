pipeline{

    agent any

    stages{
        stage('Git checkout '){
            steps{
                script{
                    git branch: 'main', url: 'https://github.com/hamzashoul/java-app-jenkins.git'
                }
            }
        }

    }


}