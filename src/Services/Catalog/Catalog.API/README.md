### Catalog API

# Run Dockerfile.development

//This build and publish the .dll
docker-compose -f docker-compose.yml build catalog.api

docker-compose -f docker-compose.yml -f docker-compose.development.yml up catalog.api
