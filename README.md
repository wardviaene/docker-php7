# docker-php7
Docker build for php7
## Usage
* create php7 repository in ECR
* sudo pip install awscli
* `aws ecr get-login --region eu-west-1`
* docker build -t php7 .
* docker tag php7:latest AMAZONUSERID.dkr.ecr.eu-west-1.amazonaws.com/php7:latest
* docker push AMAZONUSERID.dkr.ecr.eu-west-1.amazonaws.com/php7:latest
