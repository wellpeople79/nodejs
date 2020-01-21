# nodejs
nodejs study

# npm 관련 명령어
npm init : 새로운 프로젝트나 패키지를 만들때 사용하며 packages.json파일이 생성됨

npm install express --save : express 모듈을 설치하고 --save옵션으로 package.json에 등록함


# git 명령어
git add .  :  commit 전단계로 local에 추가

git add <<추가할파일이름>> : 특정파일 추가

git add --all : 한번에 모든 파일 추가

git commit -m " Commit message" : git 저장소로 저장

git commit -m "<변화한 내용>" : local에 수정된 내용 추가

git push origin master : git 서버에 저장

# socket.io
io.sockets.emit() : 연결된 모든 client 전송

socket.emit() : 현재 socket 연결된 client만 전송

socket.broadcast.emit() : 현재 socket 연결된 client를 제외한 모든 client 전송
