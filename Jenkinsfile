pipeline {
    agent any
    stages {
        stage('make python file'){
            steps{
                //Make the file
                sh "chmod +x ./make-python.sh"
                sh "./make-python.sh"
            }
        }
        stage('run python script'){
            steps{
                //Run the script with Python 3
                sh 'python3 helloworld.py'
            }
        }
    }
}