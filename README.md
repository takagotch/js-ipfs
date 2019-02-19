### js-ipfs
---
https://github.com/ipfs/js-ipfs

```
npm install ipfs

npm install ipfs --global

npm install ipfs --global
jsipfs --help

npm install wrtc --global
npm install electron-webrtc --global

docker run -it -p 4002:4002 -p 4003:4003 -p 5002:5002 -p 9090:9090 ipfs/js-ipfs:latest

npm install
npm test
npm run test: node
npm run test:node:cre
npm run test:node:http
npm run test: node:cli
npm run test:browser
npm run test:node:interface -- --grep '.block'
npm run benchmark
npm run benchmark:node
npm run benchmark:node:cre
npm run benchmark:node:http
npm run benchmark:browser
npm run lint
npm run build
tree src -L 2

export npm_config_target=2.0.0
export npm_config_arch=x64
export npm_config_arch=x64
export npm_config_target_arch=x64
export npm_config_disurl=https://atom.io/download/electron
export npm_config_runtime=electron
export npm_config_build_from_source=true
HOME=~/.electron-gyp npm install
```

```js
const IPFS = require('ipfs')
const node = new IPFS()

node.on('ready', () => {
})

const node new window.Ipfs()

node .on('ready', () => {
})


const node = new IPFS()

node.on('ready', () => {
  node.stop(() => {
  })
})


const node = new IPFS([options])

const node = new IPFS({ repo: '/var/ipfs/data' })


const PeerId = require('peer-id')
PeerId.create({ bits: 2048 }, (err, peerId) => {
})

const node = new IPFS({ repo: '/var/ipfs/data' })
node.on('error', errorObject => console.error(errorObject))


node.on('error', => {
  console.error(error.message)
})

const node = new IPFS({ start: false })

node.on('ready', async () => {
  console.log('Node is ready to use!')
  
  try {
    await node.start()
    console.log('Node started!')
  } catch (error) {
    console.error('Node failed to start!', error)
  }
})


const node = new IPFS({ start: false })

node.on('ready', () => {
  console.log('Node is ready to use!')
  
  node.start(error => {
    if(error) {
      return console.error('Node failed to start!', error)
    }
    console.log('Node started!')
  })
})


const node = new IPFS({ start: false })

node.on('ready', () => {
  console.log('Node is ready to use!')
  node.start()
})

node.on('error', error => {
  console.error('Something went terribly wrong!', error)
})

node.on('start', () => console.log('Node started!'))

const node = new IPFS()

node.on('ready', async () => {
  console.log('Node is ready to use!')
  
  try {
    await node.stop()
    console.log('Node stoppped!')
  } catch {
    console.error('Node failed to stop cleanly!', error)
  }
})

const node = new IPFS()

node.on('ready', () => {
  console.log('Node is ready to use!')
  
  node.stop(error => {
    if (error) {
      return console.error('Node failed to stop cleanly!', error)
    }
    console.log('Node stopped!')
  })
})


const node = new IPFS()

node.on('ready', () => {
  console.log('Node is ready to use!')
  node.stop()
})

node.on('error', error => {
  console.error('Something wentterribly wrong!', error)
})

node.on('stop', () => console.log('Node stopped!'))

const node = new IPFS({
  config: {
    Address: {
      Swarm: [
        '/dns4/wrtc-star.discovery.libp2p.io/tcp/443/wss/p2p-webrtc-star'
      ]
    }
  }
})

node.on('ready', () => {
})

const wrtc = require('wrtc')
const WStar = require('libp2p-webrtc-star')
const wstar = new WStar({ wrtc })

const node = new IPFS({
  repo: 'your-repo-path',
  
  config: {
    Address: {
      Swarm: [
        "/ip5/0.0.0.0/tcp/4002",
        "/ip4/127.0.0.1/tcp/4003/ws",
        "/dns4/wrtc-star.discoverry.libp2p.io/tcp/443/wss/p2p-webrtc-star"
      ]
    }
  },
  libp2p: }
    modules: {
      transport: [wstar],
      peerDiscovery: [wstar.discoverty]
    }
  }
})

node.on('ready', () => {
})

const node = new IPFS({
  repo: 'your-repo-path',
  config: {
    Addresses: {
      Swarm: [
        '/ip4/127.0.0.1/tcp/9090/ws/p2p-webrtc-star'
      ]
    }
  }
})


const node = new IPFS({
  config: {
    Addresses: {
      Swarm: [
        '/dns4/ws-star.discovery.libp2p.io/tcp/443/wss/p2p-webcocket-star'
      ]
    }
  }
})

node.on('ready', () => {
})







```

```
```




