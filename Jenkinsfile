
pipeline {

agent any

stages {

stage('Build') {

steps {
javac hello.java
echo "HelloWorld"

}

}

stage('Run') {

steps {

java hello

echo "HelloWorld"
}
}
}
}
