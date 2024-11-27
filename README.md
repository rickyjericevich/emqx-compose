# emqx-compose

A compose file to deploy the EMQX MQTT broker.

# Description
See the following:
- [EMQX Github repo](https://github.com/emqx/emqx)
- [EMQX Broker setup config](https://www.emqx.io/docs/en/v5.2/configuration/configuration.html)
- [Example EMQX configs](https://github.com/hivemq/hivemq-community-edition/tree/master/src/distribution/conf)
- [EMQX's Docker guide](https://www.emqx.io/docs/en/v5.2/deploy/install-docker.html#use-docker-compose-to-build-an-emqx-cluster)

# Usage
## 1. Make sure docker is installed
Follow this repo to set up Docker: [docker-setup-on-linux](https://github.com/rickyjericevich/docker-setup-on-linux)

## 2. Run the compose file in detached mode
```
docker compose up -d
```

## 3. Test the connection
Go the broker's dashboard at http://IP:18083/#/dashboard

You can also go to http://www.emqx.io/online-mqtt-client and connect to the broker using the host machine's IP & websocket port