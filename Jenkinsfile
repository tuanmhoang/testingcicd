pipeline {
    agent any
    
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
