pipeline {
    agent any
    stages {
        stage("hello") {
            steps {
                echo "welcome to Jenkins pipeline"
            }
        }
        stage("TEST BUILD") {
            steps {
                echo "BUILD SUCCESS"
            }
        }
        stage("DEPLOY BUILD") {
            steps {
                echo "DEPLOY SUCCESS"
            }
        }
        stage("UPLOAD BUILD DATA") {
            steps {
                echo "BUILD DATA UPLOADED"
            }
        }
        stage('To Check Installed Version Via JenkinsFile') {
            steps {
                sh '''
                  ansible --version
                  ansible-playbook --version
                  ansible-galaxy --version
                  '''
            }
        }
        
        stage("Ended") {
            steps {
                echo "BUILD DATA UPLOADED"
            }
        }
    }
}
