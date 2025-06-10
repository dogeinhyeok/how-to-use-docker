FROM nginx:latest

# largeJunk.txt 파일을 컨테이너의 index.html로 복사합니다.
# .dockerignore에 largeJunk.txt가 있으면 이 파일이 복사되지 않아 빌드에 실패합니다.
COPY largeJunk.txt /usr/share/nginx/html/index.html

CMD ["nginx", "-g", "daemon off;"]
