docker-compose down
docker volume rm qdrant_storage
docker pull qdrant/qdrant:latest
docker-compose up -d

пауза 30 секунд

docker logs qdrant

docker-compose down && docker-compose up -d
