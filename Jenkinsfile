#!groovy
pipeline {
    agent any
        stages {
            stage ('Compile stage') {
                steps {
                echo "first step on first stage"
				
                      }
                }
            stage ('package stage') {
                steps {
                  echo "first step on second stage"
				  touch 1.txt 2.txt

                  }
                }
            stage ('archive stage') {
                steps {
                echo "deployed"  
				ls ./
				 }
				}
			
			stage ('Cleaning Workspace'){
				steps{
					deleteDir()
				}
			}
		  
        }
  } 
