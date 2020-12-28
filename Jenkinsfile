pipeline {
    agent any
    stages { 
        stage('Bulid') {
            steps {
                sh '/opt/maven/apache-maven-3.6.3/bin/mvn clean sonar:sonar -Dsonar.host.url=http://ec2-54-169-220-32.ap-southeast-1.compute.amazonaws.com:9000 -Dsonar.login=admin -Dsonar.password=admin'
            }
        }
    }
}
