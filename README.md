# masa finance node

## Installing

1. Run the script:

```sh
. <(wget -qO- sh.f5nodes.com) masa
```

2. Wait till the end of installation, then enter your nodename in the input.

## Commands

#### Check node logs:

```sh
journalctl -u masad -f -o cat
```

**CTRL + C** to exit logs

#### Open node menu:

```sh
geth attach ipc:$HOME/masa-node-v1.0/data/geth.ipc
```

#### Menu options:

check sync status

```sh
eth.syncing
```

check peers count

```sh
net.peerCount
```

**CTRL + D** to exit menu
