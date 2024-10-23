@Library('jenkins-shared-library') _

pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Building image , hey'
                echo 'Testing auto build'
                script{
                    build()
                  }
            }
        }
       stage('testing') {
            steps {
                echo 'testing....'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying....'
            }
        }
    }
}
