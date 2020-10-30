pipeline {
    agent any
    stages {
        stage('make python file'){
            steps{
                //Make the file
                sh 'touch helloworld.py'
                //sh 'echo "print('hello world')" > helloworld.py'
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