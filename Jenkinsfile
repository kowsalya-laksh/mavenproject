node{
stage('scm-git checkout'){
git 'https://github.com/kowsalya-laksh/mavenproject'
}
stage('compile stage'){
def mvnHome = tool name: 'MAVEN_HOME', type: 'maven'
sh "${mvnHome}/bin/mvn compile"
}
}
