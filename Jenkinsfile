pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac Sample.java'     //for window based execution bat and linux based sh
		
            }
        }
        stage('Run') {
            steps {
                bat 'java Sample'
            } 
        }
    }
}
