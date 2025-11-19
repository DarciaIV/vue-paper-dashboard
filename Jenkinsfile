pipeline {
    agent any

    stages {
        stage('Cloning our GIT project') {
            steps {
                git url: 'https://github.com/DarciaIV/vue-paper-dashboard'
            }
        }
        stage('Show README.md') {
            steps {
                sh 'ls -l'
                sh 'cat README.md'
            }
        }
      stage('Show NewFile1') {
            steps {
                sh 'echo JENKINS >> NewFile1'
                sh 'cat NewFile1'
            }
        }
    }
}
