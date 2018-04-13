pipeline {
    agent none
    stages {
        stage('Run Tests'){
            steps {
                sh "echo buid"
                }
            }
        stage('Run Tests') {
            parallel {
                stage('Windows') {
                    steps {
                        sh "echo Windows"
                        }
                    }
                stage('Mac') {
                    steps {
                        sh "echo Mac"
                        }
                    }
                }
            }
        }
    }
