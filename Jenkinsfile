pipeline {
    agent any
    stages {
        stage('make python file'){
            //Make the file
            sh 'touch helloworld.py'
            sh 'echo "print('hello world')" > helloworld.py'
        }
        stage('run python script'){
            //Run the script with Python 3
            python3 helloworld.py
        }
    }
}