# yaraft
[![Build Status](https://travis-ci.org/neverchanje/yaraft.svg)](https://travis-ci.org/neverchanje/yaraft)

yaraft is a C++11 port of [etcd/raft](https://github.com/coreos/etcd/tree/master/raft).

## Features

- [x] Leader Election
- [x] Log Replication
- [x] PreVote
- [ ] CheckQuorum
- [x] Log Compaction / InstallSnapshot
- [ ] Flow Control
- [x] Single-Node Cluster
- [ ] Read-only
- [ ] Leader Transfer
- [x] Reconfiguration

## Installation

```bash
sudo apt-get -y install libboost-dev
bash install_deps_if_neccessary.sh
cd build && cmake .. && make && make install
```

## License

yaraft is under the Apache 2.0 license. See the LICENSE file for details.
