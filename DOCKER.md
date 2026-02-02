# DOCKER

cd /app

docker build -f Dockerfile-22 -t todo:25 .
docker scout quickview

docker run -d -p 3000:3000 --name todo todo:25

# GIT 

git init 
git remote add origin https://github.com/Aymanovick/TODO-JS.git
git branch -M main
