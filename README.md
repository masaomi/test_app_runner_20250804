## Rails Hello World for AWS App Runner

This is a minimal Docker-based Rails 8.0.2 + Ruby 3.3.7 project for AWS App Runner.

### Docker build

```bash
docker build -t hello_world .
aws ecr get-login-password --region eu-central-1 | docker login --username AWS --password-stdin 415088266017.dkr.ecr.eu-central-1.amazonaws.com\n
```

