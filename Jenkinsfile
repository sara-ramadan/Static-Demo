pipeline {
    agent any
    stages {
        stage('Lint HTML') {
            steps {
                echo 'Building Container..'
		tidy -q -e *.html 

            }
        }
    }
}
