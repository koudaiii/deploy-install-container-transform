sample deploy ECS by docker-compose.yml
---


```
deploy:
  steps:
    - koudaiii/install-container-transform:
        key: $AWS_KEY
        secret: $AWS_SECRET
        region: $AWS_REGION
        cluster: $AWS_ECS_CLUSTER
        definition: $AWS_ECS_DEFINITION
        count: $AWS_ECS_COUNT
```
