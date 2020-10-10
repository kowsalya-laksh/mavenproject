node{
  def mvnHome = tool name: 'MAVEN_HOME', type: 'maven'
stage('scm-git checkout'){
git 'https://github.com/kowsalya-laksh/mavenproject'
}
stage('Build'){
sh "${mvnHome}/bin/mvn validate compile -f pom.xml"
}
}
