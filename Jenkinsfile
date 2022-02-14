pipeline {
    agent any
    
    parameters {
        string(name: 'nameOfJob', defaultValue: 'BuilderApp', description: 'Name of the job')
    }
    
    stages {
        stage('Prepare') {
            steps {
                echo "Invoking job ${params.nameOfJob}"
            }
        }
        stage('Download') {
            steps {
                echo 'Dowloading from SCM stage'
            }
        }
    }
}
