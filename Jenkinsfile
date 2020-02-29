pipeline {
    agent any
    stages {
        stage('Lint HTML') {
            when {
                branch 'Jenkins'
            }
            steps { 
                tidy -q -e *.html
                }
            }
        }
    }
}
