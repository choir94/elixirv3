# Testnet v3 Validator Setup Guide

## Recommended Hardware Requirements 

|   SPEC      |        Recommend          |
| :---------: | :-----------------------: |
|   **CPU**   | 4 Cores (ARM64 or x86-64) |
|   **RAM**   |        4 GB (DDR4)        |
|   **SSD**   |        100 GB          |
| **NETWORK** |        100 Mbps           |


## Automatic Install
```
cd $HOME && source <(curl -s https://raw.githubusercontent.com/choir94/elixirv3/main/elixirv3.sh)
```
### Check log
```
sudo docker logs -f elixir
```
### Upgrade
```
docker kill elixir
docker rm elixir
docker pull elixirprotocol/validator:v3
```

### Stop and Remove Node
```
sudo docker stop elixir
sudo docker rm elixir
rm -r $HOME/elixir
```



### Dashboard: https://testnet-3.elixir.xyz/

### Join Channel Telegram

