pipeline {
    agent any
    tools {
        maven 'Maven 3.6.3' // Jenkins에 설정된 Maven 설치 이름과 일치해야 합니다.
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
