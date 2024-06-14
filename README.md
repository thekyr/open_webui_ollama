### Run ollama localy using open-webui with podman.

Run ollama using open-webui locally and  No GPU is needed. 

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

