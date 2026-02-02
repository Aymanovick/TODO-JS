# DOCKER

cd /app

docker build -f Dockerfile-22 -t todo:22 .

docker run -d -p 3000:3000 --name todo-app-22 todo:22