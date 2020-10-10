node{
stage('scm-git checkout'){
git 'https://github.com/kowsalya-laksh/mavenproject'
}
stage('Build'){
  def mvnHome = tool name: 'MAVEN_HOME', type: 'maven'
  bat "mvn validate compile -f pom.xml"
}
}
