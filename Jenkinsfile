pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // Step 1: Checking out code from the repository
                    echo 'Step 1: Checking out the code'
                    checkout scm  // This will pull code from your Git repository
                }
                script {
                    // Step 2: Running the script
                    echo 'Step 2: Running the Hello World script'
                    // Run the shell script or Python script here
                    // sh './hello.sh'   // For a shell script
                    sh 'python hello.py'  // Uncomment this for a Python script
                }
            }
        }

        stage('Test') {
            steps {
                script {
                    // Step 3: Placeholder for testing
                    echo 'Running a test in the Test stage.'
                }
            }
        }

        stage('Deploy') {
            steps {
                script {
                    // Step 4: Placeholder for deployment
                    echo 'Deploying the application in the Deploy stage.'
                }
            }
        }
    }
}
