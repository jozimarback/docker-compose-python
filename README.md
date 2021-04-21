# Docker compose python

Projeto aprendizado criação de containers com docker compose.
- MongoDB
- Python
- Frontend jquery

## Para subir 🚀
docker-compose up

### Escalando containers workers 
docker-compose up -d  --scale worker=3

### Ouvindo containers worker
docker-compose logs -f -t worker