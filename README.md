#Lanzar docker con Selenium Grid Firefox
docker run -d -p 4444:4444 -p 5901:5900 -v /dev/shm:/dev/shm selenium/standalone-firefox:4.0.0-beta-1-prerelease-20210201

#Conectarse a través de VNC a este servidor
127.0.0.1:5901
