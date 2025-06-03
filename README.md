# xmtp-local-node

Use this repo to easily launch a local XMTP node for app development and testing purposes.

## Prerequisites

One of the following installed and running: [Docker Desktop](https://docs.docker.com/get-docker/), [Orbstack](https://orbstack.dev/), or similar.

## Launch a local XMTP node

Run the `up` bash script:

```shell
./up
```

This will download and start all Docker containers to run an XMTP node.

## Connect an XMTP client to a local node

To configure your XMTP client to connect to the local XMTP node, set the `env` [client option](https://docs.xmtp.org/inboxes/create-a-client#configure-an-xmtp-client) to `local`.

## Stop the local XMTP node

Run the `down` bash script:

```shell
./down
```
