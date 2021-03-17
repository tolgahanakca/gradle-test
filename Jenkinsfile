pipeline {
        agent any 
        stages {
            stage('Build') {
                steps {
                    echo 'Build Starts!'

                    bat "${workspace}/build.gradle"
                    echo 'Build Ends'
                }
            }

            stage('Test') {
                steps {
                    echo 'Test Starts!'
                    bat  "${workspace}/src"
                    echo 'Test Ends'
                }
            }

            stage('Deploy') {
                steps {
                    echo 'Deploy Starts!'
                    bat  "${workspace}/gradle/wrapper”
                    echo 'Deploy Ends'
                }
            }
        }
    }
