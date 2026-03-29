#  Chaindata Snapshot

Snapshot at block **287921**

## Quick Start
```bash
apt update && apt install -y zstd
```

```bash
wget https://github.com/CypherTroopers/tar/releases/download/287921/chaindata0-287921.tar.zst \
&& wget https://github.com/CypherTroopers/tar/releases/download/287921/chaindata0-287921.tar.zst.sha256 \
&& sha256sum -c chaindata0-287921.tar.zst.sha256 \
&& tar -I zstd -xvf chaindata0-287921.tar.zst
```
