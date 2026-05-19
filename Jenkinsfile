pipeline{
    agent {
        label 'app-slave'
    }
    stages{
        stage ('Build'){
            steps{
                echo " Hello from build step"
            }
        }
        stage ('hostname'){
            steps{
                sh 'hostname -i'
            }
        }
    }
}
