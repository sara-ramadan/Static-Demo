pipeline {
    agent any
    stages {
        stage('Lint HTML') {
            steps { 
                tidy -q -e *.html
                }
            }
        }
    }
}
