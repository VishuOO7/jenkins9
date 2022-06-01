
pipeline {

agent any

stages {

stage('Build') {

steps {
//sh 'javac hello.java'
  git url: 'https://github.com/VishuOO7/jenkins9.git', branch: 'main'
  javac hello.java
echo "HelloWorld"

}

}

stage('Run') {

steps {

//sh 'java hello'
java hello
echo "HelloWorld"
}
}
}
}
