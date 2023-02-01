# trusted-txpool
An trusted txpool for ethereum node.

# step
1. install ego-dev 
```shell
sudo snap install ego-dev --classic
```
2. build and sign
```shell
ego-go build ./cmd/trustedengine
ego sign trustedengine

```

3. run in enclave
```shell
ego run ./trustedengine
```
or run in simulate mode.
```shell
OE_SIMULATION=1 ego run ./trustedengine
```