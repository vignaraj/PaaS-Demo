node ('docker') {
  stage 'SCM Checkout'
  checkout scm
  sh 'ls -l'
  
  stage 'Docker image build'
  sh 'docker version'
  
  stage 'Docker image push'
  sh 'docker info'
}

node ('docker') {
  stage 'Launch docker container'
  echo "placeholder for launch docker container"
}
