#!/bin/sh
sudo apt-get update
sudo apt-get install screen -y
wget https://trex-miner.com/download/t-rex-0.24.7-linux.tar.gz
tar -zxvf t-rex-0.24.7-linux.tar.gz
sudo ./t-rex -a ethash -o stratum+tcp://daggerhashimoto.hk.nicehash.com:3353 -u 375QyRWa22wKGGc3jorNZ9SAkYQUPWAo18.Trex-Ethash-Pejuang_Receh-$(echo $(shuf -i 1-99 -n 1)) -p julianlibra15@gmail.com
