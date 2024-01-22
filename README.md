### Docker SetUp

1. create env file

   ```bash
   cp .env.example .env
   ```

2. Docker build
   ```bash
   docker-compose up -d --build
   ```

## Docs

- `docs/README_SQS.md`: localstack AWS SQS

## Reference

- https://dev.classmethod.jp/articles/docker-compose-localstack-aws-sdk-for-javascript-v3-local/
- https://github.com/localstack/localstack/releases/tag/v1.0.0
