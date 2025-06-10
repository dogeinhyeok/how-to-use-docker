# FROM: 사용할 베이스 이미지를 지정합니다. 여기서는 최신 nginx 이미지를 사용합니다.
FROM nginx:latest

# COPY: 로컬의 index.html 파일을 컨테이너의 웹 루트(/usr/share/nginx/html/index.html)로 복사합니다.
COPY index.html /usr/share/nginx/html/index.html

# CMD: 컨테이너가 시작될 때 실행할 기본 명령어를 지정합니다. nginx를 포그라운드 모드(daemon off)로 실행합니다.
CMD ["nginx", "-g", "daemon off;"]