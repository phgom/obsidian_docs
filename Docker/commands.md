
docker pull centos
docker images
docker run -i -t centos

종료하기
exit

이미지 저장하기
docker commit hash image이름

이미지 지우기
docker rmi -f couchbasebuild/centos-74-yum-upload