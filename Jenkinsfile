pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
               sh 'git pull https://github.com/stalindominic/apache.git'
                 }
            }
        stage('install') { 
            steps {
                sh 'ansible-playbook /ansible/config.yml -i /ansible/hosts'
            }
                }
            }
        }
    }
}
