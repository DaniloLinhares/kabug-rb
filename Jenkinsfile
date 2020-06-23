<<<<<<< HEAD
pipeline {
    agent {
        docker {
            image 'ruby'
        }
    }

    stages {
        stage('Build') {
             steps {
                echo 'Building or Resolve Dependencies!'
                sh 'bundle install'
                
            }
        }
        stage('Test') {
            steps {
                echo 'Running regression tests'                
            }
        }   
        stage('UAT') {
            steps {
                echo 'Wait for User Acceptance'
                input(message: 'Go to production?', ok: 'Yes')
            }
        }   
        stage('Prod') {
            steps {
                echo 'Webapp is Ready :D'
            }
        }
    }
}
=======
pipeline {
    agent {
        docker {
            image 'ruby'
        }
    }

    stages {
        stage('Build') {
             steps {
                echo 'Building or Resolve Dependencies!'
                sh 'bundle install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running regression tests'                
            }
        }   
        stage('UAT') {
            steps {
                echo 'Wait for User Acceptance'
                input(message: 'Go to production?', ok: 'Yes')
            }
        }   
        stage('Prod') {
            steps {
                echo 'Webapp is Ready :D'
            }
        }
    }
}
>>>>>>> 8d6924e29ae07b29203bc80086b50d66ab2473dd
