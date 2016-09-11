node ('docker') {
  stage 'SCM Checkout'
  checkout scm
  
  stage 'Docker image build'
  sh 'docker version'
  
  stage 'Docker image push'
  parallel 'branch1' : {
    sh "docker info"
  }, 'branch2' : {
    sh "echo branch 2"
  }

  stage 'Launch docker container'
  echo "placeholder for launch docker container"
}
