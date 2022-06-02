
pipeline {

agent any

stages {

stage('Build') {

steps {
bat 'javac HelloWorld.java'
bat 'java -version'
  //git url: 'https://github.com/VishuOO7/jenkins9.git', branch: 'main'
  //javac HelloWorld.java
//echo "HelloWorld"

}

}

stage('Run') {

steps {

bat 'java HelloWorld'
  
//java hello
//echo "HelloWorld"
}
}
}
}
