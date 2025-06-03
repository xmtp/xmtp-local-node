# xmtp-local-node

Use this repo to easily launch a local XMTP node for app development and testing purposes.

## Prerequisites

- [Docker Desktop] installed
 
## Launch a local XMTP node

Run:

```bash
docker-compose -p xmtp -f docker-compose.yml up
```

To configure your XMTP client to connect to the local XMTP node, set the `env` [client option](https://docs.xmtp.org/inboxes/create-a-client#configure-an-xmtp-client) to `local`.
