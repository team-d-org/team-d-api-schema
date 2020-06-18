# Run
```sh
docker-compose up
open http://localhost:8080
```

# Bundle
```sh
npm install -g @apidevtools/swagger-cli
swagger-cli bundle -r -t yaml -o docs/swagger.yml api/swagger.yml
```
