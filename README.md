### Run ollama localy using open-webui with podman.

Run ollama using open-webui locally, no  GPU is needed. In case there is a GPU an nvidia driver can be configured in the docker-compose in ollama. 

#### Why run LLMs locally?

#### Models

#### Model settings

### Usage
1. Create network
  - update your the docker-compose with the defined 'network_name'
```
docker network create <network_name>
```

2. Start containers:

```
docker-compose up
```

3. Access the webui and create a local user. Download the latest ollama model.

```
http://localhost:3002
```

4. Enable GPU
To enable GPU the following can be added

```
    deploy:
      resources:
        reservations:
          devices:
            - driver: nvidia
              count: 1
              capabilities: [ gpu ]
```
