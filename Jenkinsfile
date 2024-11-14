pipeline {
agent any
environment {
    JAVA_HOME="C:/Program Files/Java/jdk-17"
  }
stages {
stage('Clean stage') {
steps {
dir("JENApp") {
bat 'C:/Users/Shivansh Sharma/Downloads/apache-maven-3.9.9-bin/mvn clean'
}
}
}
stage('Compile stage') {
steps {
dir("JENApp") {
bat 'C:/Users/Shivansh Sharma/Downloads/apache-maven-3.9.9-bin/mvn compile'
}
}
}
stage('Install stage') {
steps {
dir("JENApp") {
bat 'C:/Users/Shivansh Sharma/Downloads/apache-maven-3.9.9-bin/mvn install'
}
}
}
}
}
 
