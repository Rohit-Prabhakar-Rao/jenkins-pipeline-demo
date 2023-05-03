pipeline{
    agent any
    stages{
        stage('Git-Checkout'){
            steps{
                echo "checking out from git repo";
                git 'https://github.com/Rohit-Prabhakar-Rao/jenkins-pipeline-demo.git'
            }
        }
        stage('Deploy'){
            steps{
                echo "Deploying to stage enviroment for more tests";
                sh 'show.sh'
            }
        }
        
    }
}
