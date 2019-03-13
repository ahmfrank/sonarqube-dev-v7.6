# How to build Sonareqube developer version v7.6
# (1) Copy both Dockerfile and run.sh on same directory
# (2) To build docker container image, run command as below:
# $docker  build -t sonaerqube-dev-v7.6  ./
# $docker  run -d --name sonar-dev-v7.6 -p 9000:9000 sonaerqube-dev-v7.6
# $docker ps -a
