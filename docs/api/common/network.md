# Network

* NetConnectedness

  `NetConnectedness(context.Context, peer.ID) (network.Connectedness, error)`

* NetPeers
  
  `NetPeers(context.Context) ([]peer.AddrInfo, error)`

* NetConnect
  
  `NetConnect(context.Context, peer.AddrInfo) error`

* NetAddrsListen

  `NetAddrsListen(context.Context) (peer.AddrInfo, error)`

* NetDisconnect

  `NetDisconnect(context.Context, peer.ID) error`

## CLI

```
$ lotus net
NAME:
   lotus net - Manage P2P Network

USAGE:
   lotus net command [command options] [arguments...]

COMMANDS:
     peers    Print peers
     connect  Connect to a peer
     listen   List listen addresses
     id       Get node identity
     help, h  Shows a list of commands or help for one command

OPTIONS:
   --help, -h     show help (default: false)
   --version, -v  print the version (default: false)
```