# adguard

example for adguard k8s deployment

based on https://jmcglock.substack.com/p/running-adguard-home-on-kubernetes (many thanks for sharing!).

## changes

- using [nfs](https://microk8s.io/docs/nfs) storageclass
- fix ip on metallb
- add ressources
- add mountPath: /opt/adguardhome/conf for persisting (initial) config

tested and running on ubuntu 23.10 with microk8s