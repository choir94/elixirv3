# Testnet v3 Validator Setup Guide

## Recommended Hardware Requirements 

|   SPEC      |        Recommend          |
| :---------: | :-----------------------: |
|   **CPU**   | 4 Cores (ARM64 or x86-64) |
|   **RAM**   |        4 GB (DDR4)        |
|   **SSD**   |        100 GB          |
| **NETWORK** |        100 Mbps           |


## Install Docker Pull
```
docker pull elixirprotocol/validator:v3
```
### Create Directory
```
mkdir /home/elixir
cd /home/elixir
nano validator.env
```
### Edit File Env
```
ENV=testnet-3

STRATEGY_EXECUTOR_IP_ADDRESS= Ip Vps
STRATEGY_EXECUTOR_DISPLAY_NAME=  Nama validator
STRATEGY_EXECUTOR_BENEFICIARY= Address validator
SIGNER_PRIVATE_KEY= Privat key
```

### Start Running
```
docker run -d --env-file /home/elixir/validator.env --name elixir --restart unless-stopped elixirprotocol/validator:v3
```


### Pergi ke link testnet stake and delegate : https://testnet-3.elixir.xyz/

### Join Channel Telegram Airdrop Node
--  https://t.me/airdrop_node

