pipeline {
    agent any
    stages {
        stage('clone step') {
            steps {
                sh ' rm -rf hello-world-war.git '
                sh 'git clone https://github.com/Rajath9585/hello-world-war.git '
            }
        }
          stage('build step') {
            steps {
                sh 'mvn package'  
    }
}
    }
}
