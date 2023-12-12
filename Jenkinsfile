pipeline {
  agent any

  tools {
     maven "jenkin-maven"
      }


   stages {
         stage('build') {
              steps {
                      git 'https://github.com/ashwin1-dev/12-dec-23-war.git'
                      sh "mvn clean package"
                    }
                   }
             }
}

