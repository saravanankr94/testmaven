node {
  stage 'build 1'
  sh 'pwd'
  stage 'build 2'
  git url: 'https://github.com/saravanankr94/testmaven.git'
  stage 'build 3'
  def mvnHome = tool 'M4'
  stage 'build 4'
  sh "${mvnHome}/bin/mvn -B verify"
}
