# fivem-api-pack

A Node.js package for interacting with FiveM servers And Getting server information.

## Installation

Install the package using npm:

```bash
npm install fivem-api-pack
```

## Usage
###  Fetch Server Name
```JS
const serverInfo = require('fivem-api-pack');

const serverIP = 'xxx.xxx.xxx.xxx';
const serverPort = 'xxx';

serverInfo.getServerInfo(serverIP, serverPort)
  .then(data => {
    const serverName = serverInfo.getServerName(data);
    console.log('Server Name:', serverName);
  })

```



