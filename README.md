### Docker SetUp

1. Docker build
   ```bash
   docker-compose up -d --build
   ```

2. exec localstack container
   ```bash
   docker exec -it localstack_main bash
   ```
   
3. Set aws config
    ```bash
    aws configure
    
    >>>
    AWS Access Key ID [None]: test
    AWS Secret Access Key [None]: test
    Default region name [None]: ap-northeast-1
    Default output format [None]: json
    ```
   
4. setup file
    ```bash
    export AWS_CONFIG_FILE
    ```
   
### AWS SQS Get Stared


## Ref
* [POSTMAN AWS SQS](https://documenter.getpostman.com/view/2631434/SWLh56pX#intro)