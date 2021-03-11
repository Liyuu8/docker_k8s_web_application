docker build -t weblog-db:v1.0.0 .
docker run -d weblog-db:v1.0.0
docker exec -it gifted_heisenberg sh