
pipeline {

agent any

stages {

stage('Build') {

steps {
bat 'javac hello.java'
bat 'java -version'
  //git url: 'https://github.com/VishuOO7/jenkins9.git', branch: 'main'
  //javac hello.java
//echo "HelloWorld"

}

}

stage('Run') {

steps {

bat 'java hello'
  
//java hello
//echo "HelloWorld"
}
}
}
}
