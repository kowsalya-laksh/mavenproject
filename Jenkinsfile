node{
  //def mvnHome = tool name: 'MAVEN_HOME', type: 'maven'
stage('scm-git checkout'){
git 'https://github.com/kowsalya-laksh/mavenproject'
}
stage('Build'){
sh C:\Program Files\apache-maven-3.6.3/bin/mvn validate compile -f pom.xml"
}
}
