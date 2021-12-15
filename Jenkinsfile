def tomcatWeb = 'C:\\Users\\AMBUJ\\Downloads\\apache-tomcat-9.0.55-windows-x64\\apache-tomcat-9.0.55\\webapps'
// def tomcatBin = 'C:\\Users\\AMBUJ\\Downloads\\apache-tomcat-9.0.55-windows-x64\\apache-tomcat-9.0.55\\bin'
// def status = ''

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
      
//        stage('Test') {
//             steps {
//                 bat 'mvn test'
//             }
//         }
      
//         stage('Packaging') {
//             steps {
//                 bat 'mvn package'
//             }
//         }
//         stage('Deploying') {
//             steps {
//                 bat "copy target\\blink.war \"${tomcatWeb}\\blink.war\""
//             }
//         }
    }
}
