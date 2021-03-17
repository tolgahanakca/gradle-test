pipeline {
        agent any 
         stages {
                 stage('Compile') {
                           steps {
                                  gradlew('clean', 'classes')
            }
                  stage('Build') {
                            steps {
                                           echo 'Build Starts!'

                    
                                          echo 'Build Ends'
                }
            }

                  stage('Test') {
                           steps {
                                       echo 'Test Starts!'
                    
                                          echo 'Test Ends'
                }
            }

                   stage('Deploy') {
                            steps {
                                            echo 'Deploy Starts!'
                    
                                            echo 'Deploy Ends'
                }
            }
        }
    }
