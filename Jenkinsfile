pipeline{
     agent any 
     stages{
        stage('build'){
            steps{
                sh 'npm install'
            }
            stage('test'){
                sh 'Echo test is running'
            }
            stage ('deploy'){
                sh'echo "deploying the application'
            }
        }
     }
}