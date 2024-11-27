Run `curl http://localhost:3000/products/1`


# Sonar
`docker run -p 9000:9000 sonarqube:latest`

`npm run sonar`


# To run k6 tests
` k6 run --out influxdb=http://localhost:8086 test.ts`