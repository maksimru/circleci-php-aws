#Official circle ci php 7 image with bundled aws
Contains some php packages, google cloud sdk include kubectl, aws-cli, dockerize, remote docker client

#Environment vars for automatic auth to AWS
docker run -it -e AWS_ACCESS_KEY_ID=XXXXX -e AWS_SECRET_ACCESS_KEY=XXXXX -e AWS_DEFAULT_REGION=us-east-1 maxmtmn/circle-php-aws /bin/bash