node (docker) {
  stage 'SCM Checkout'
  checkout scm
  
  stage 'Docker image build'
  sh 'echo docker version'
  
   
  stage 'Another step'
  sh 'echo docker version'
  
  stage 'Docker image push'
  parallel 'branch1' : {
    sh "echo docker info"
  }, 'branch2' : {
    sh "echo branch 2"
  }

  stage 'Launch docker container'
  echo "placeholder for launch docker container"
}
