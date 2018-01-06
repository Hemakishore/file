node {
   
   	stage 'Stage 1'
   		echo 'Hello there, this is testshell scripts'
   	stage 'Checkout'
   		git url: 'https://github.com/malli2017/file.git'
   	stage 'Build'
   		sh './myBuild.sh'
   	stage 'Deploy'
   		sh './myDeployment.sh'
  
}
