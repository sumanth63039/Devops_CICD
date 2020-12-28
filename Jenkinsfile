pipeline {
    agent any
    stages { 
        stage('Bulid') {
            steps {
                sh '/opt/maven/apache-maven-3.6.3/bin/mvn clean verify sonar:sonar'
            }
        }
    }
}
