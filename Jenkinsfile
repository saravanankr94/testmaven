node {
  stage 'build1'
  git url: 'https://github.com/saravanankr94/testmaven.git'
  def mvnHome = tool 'M3'
  sh "${mvnHome}/bin/mvn -B verify"
}
