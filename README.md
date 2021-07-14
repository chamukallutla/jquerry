# jquerry
aws ecr get-login-password --region us-east-2 |sudo docker login --username AWS --password-stdin 405740401707.dkr.ecr.  us-east-2.amazonaws.com
sudo docker build -t 405740401707.dkr.ecr.us-east-2.amazonaws.com/juqerry:$BUILD_NUMBER .
sudo docker push 405740401707.dkr.ecr.us-east-2.amazonaws.com/juqerry:$BUILD_NUMBER 

