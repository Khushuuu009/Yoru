pipeline {
 agent any
 environment {
 // Set JAVA_HOME to the path of your Java 17 installation
 JAVA_HOME = 'C:/Program Files/Java/jdk-17'
 // Add Java bin directory to PATH
 PATH = "${JAVA_HOME}\\bin;${env.PATH}"
 }
 tools {
 maven 'Maven'
 }
 stages {
 stage('GetCode') {
 steps {
 git branch: 'main', url: 'https://github.com/Khushuuu009/Yoru.git'
 }
 }

 }
}
