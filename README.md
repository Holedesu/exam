# Построить образ
docker build -t simple-app .

# Запустить контейнер
docker run -p 3001:3000 simple-app
