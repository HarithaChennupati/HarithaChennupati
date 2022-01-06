pipeline {
  agent any
  stages {
    stage('clone repo data') {
      steps {
        bat 'git clone https://github.com/HarithaChennupati/HarithaChennupati.git'
      }
    }

    stage('copy to webapps') {
      steps {
        bat 'COPY "C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\Sample_main\\sample.war" "C:\\Program Files\\Apache Software Foundation\\Tomcat 9.0\\webapps"'
      }
    }

  }
}