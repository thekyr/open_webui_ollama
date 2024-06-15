### Run ollama localy using open-webui with podman.

Run ollama using open-webui locally, no  GPU is needed. In case there is a GPU add nvidia driver in the docker-compose. 

#### Why run LLMs locally?

#### Models

#### Model settings

### Usage
1. Create network

```
podman network create <network_name> ### as defined in podman-compose.yml
```

2. Start containers:

```
podman-compose up -d
```

