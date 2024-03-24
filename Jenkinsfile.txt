pipeline {
    agent any

    stages {
        stage('git pull source code') {
            steps {
                git branch: 'main', url: 'https://github.com/samapti14/delete-me.git'
            }
        }
    }
}
