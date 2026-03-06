

  pipeline {
    agent any
    parameters {
        string(name: 'PROJECT_NAME', defaultValue: 'MyProject', description: 'Name of the project')
    }
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/logeshlokesh2005-maker/cat1.git'
            }
        }
        stage('Display') {
            steps {
                echo "The project name is: ${params.PROJECT_NAME}"
            }
        }
    }
}
