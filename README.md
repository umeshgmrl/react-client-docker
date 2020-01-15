```
docker build -f Dockerfile.dev -t bhumesh/react-docker .
docker run -p 3000:3000 c8de2fa51b68
docker run -p 3000:3000 -v ${pwd}:/app c8de2fa51b68


docker build -f Dockerfile.dev -t bhumesh/react-docker .
docker run d744979c2801 npm run test
docker exec -it d744979c2801 npm run test
```