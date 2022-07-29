# PITAK SERVER

Before you can build this, you MUST download a TAKSERVER-DOCKER-X.X-RELEASE.zip from official source. Without this archive you won't be able to run TAK server on your RaspberryPi. Please check release checksums on don't use unofficial sources.

## Requirements
- Docker
- A TAK server release
- 4GB memory
- Network connection 

## Installation

Fetch this git repo and cd into the directory

    git clone https://github.com/45clouds/pitak.git
    
### ARM64 setup (Pi4)

```
cd pitak
chmod +x scripts/setup-arm.sh
./scripts/setup-arm.sh
```

### Clean up
```
./scripts/cleanup.sh
```

