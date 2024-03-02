1. 리눅스 기반으로 설명함.
2. Home/유저 하위에서 git clone 한다.
3. git clone 한 폴더 들어가서 backend, frontend, mysql, web 이름의 폴더를 생성한다.
4. .env를 열어서 열고 싶은 PORT로 수정한다.
5. frontend 폴더 하위에 frontend 소스를 넣는다. (EX. REACT)
6. backend 폴더 하위에 backend 소스를 넣는다. (EX. Spring boot 일 때 jar도 있어야함.)
7. web 폴더 하위에 data/conf/, data/www/ 이렇게 폴더 각각 만들자
8. web 폴더 하위에 nginx/conf/ 폴더 만들고 하위에 nginx.conf 파일 만들고 안에 넣을 설정을 넣어준다.
9. docker-compose up -d 로 실행 후 해당 서버의 port 80(기본 웹포트)로 열어서 사용하면 된다.
10. 처음 빌드할 때만 오래 걸릴 것이다. 도커 images는 알아서 다운 받아짐.
