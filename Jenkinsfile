pipeline{
    agent any
    stages{
        stage('FirstStage'){
            steps{
                sh 'hostname -i'
            }
        }
        stage('SecondStage'){
            agent{
                label 'app-slave'
            }
            steps{
                sh 'hostname -i'
            }
        }
    }
}
