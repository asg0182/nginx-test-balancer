# nginx-test-balancer
Simple test nginx balancer

Please make sure you have docker installed and port 80 is not listen

1 Just clone repo

2 Run this commands
```bash
docker network create backend
cd ./nginx-test-balancer
docker-compose up --build
```

Try a few times in browser http://localhost
