pipeline {
    agent any

    environment{
        PROJECT_NAME = "Zalupa"
        OWNER_NAME   = "Volodya"
    }

    stages {
        stage('1-Build') {
            steps {
                echo "Start of Stage Build"
                echo "Building......."
                echo "End of Stage Build"
            }
        }
        stage('2-Test') {
            steps {
                echo "Start of Stage Test"
                echo "Testing......."
                sh  "cat /etc/passwd"
                echo "End of Stage Build"
            }
        }
        stage('3-Deploy') {
            steps {
                echo "Start of Stage Deploy"
                echo "Deploying......."
                sh '''
                echo "rabotay"
                echo "Yamborghini High"
                '''
                echo "Hello $OWNER_NAME"
                echo "Project $PROJECT_NAME"
                echo "End of Stage Build"
            }
        }
    }
}
