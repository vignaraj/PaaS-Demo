node ('docker') {
  stage 'SCM Checkout'
  checkout scm
  
  stage 'Docker image build'
  docker version
  
  stage 'Docker image push'
  docker info
}

node ('docker') {
  stage 'Launch docker container'
  echo "placeholder for launch docker container"
}
