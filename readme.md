baenux/mfds

- *.bat 내부
<h3>
@echo off

docker rm -f mfds
start http://localhost:5000
docker rm -f mfds docker run -it --name mfds -p 5000:5000 {name/repositories:tag}

exit
</h3>

* 버전별 설명
-- ver0.1.4 - 0429작업본 / app - 0429 / ftp - 1.3 /DB - 146(app, ftp 변경 필요) 

-- 실행 시 
- 인터넷 창 실행
- bashrc 내에서 코드 실행 -> sh로 실행
- 한 터미널에서 동시실행 -> app, ftp
