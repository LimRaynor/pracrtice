## 컨테이너 생성
옵션 → 컨테이너를 어떻게 만들지
인자 → 컨테이너 안에서 뭘 실행할지
docker run (옵션) 이미지 (인자)
## 컨테이너 삭제
docker stop 컨테이너_이름
## 컨테이너 실행
docker rm 컨테이너_이름
##  컨테이너 정지
docker ps -a
##  엔진 시작
sudo systemctl start docker
##  엔진 종료
sudo systemctl stop docker
##  자동 실행 설정
sudo systemctl enable docker