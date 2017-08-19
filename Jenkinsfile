node {
  stage 'build 1'
  sh 'mv test_pipeline test_pipeline_v1.1'
  stage 'build 2
  git url: 'https://github.com/saravanankr94/testmaven.git'
  stage 'build 2'
  def mvnHome = tool 'M3'
  stage 'build 4'
  sh "${mvnHome}/bin/mvn -B verify"
}
