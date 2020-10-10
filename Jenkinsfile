node{
stage('scm-git checkout'){
git 'https://github.com/kowsalya-laksh/mavenproject'
}
stage('Build'){
  def mvnHome = tool name: 'MAVEN_HOME', type: 'maven'
  sh "${mvnHome}/bin/mvn validate compile -f mavenproject/pom.xml"
}
}
