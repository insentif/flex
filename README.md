# flex
Algoritma ini digunakan pada coin:
1. [LCN](https://lcnxp.com/address/lc1q8wcgexr6gzhxu3pmkecxtyj2htd5jaxmu3mpx3)
2. [KCN](https://kcnxp.com/address/kc1q5ed6nnk2jvxdltefwq8tjlvne85tnp506ugj7z)
3. [Flex](https://github.com/f1exlabs/cpuminer/releases)

[zpool](https://zpool.ca/wallet/kc1q5ed6nnk2jvxdltefwq8tjlvne85tnp506ugj7z)  
```sh
cpuminer-aes-sse42.exe -a flex -o stratum+tcp://flex.sea.mine.zpool.ca:3340 -u kc1q5ed6nnk2jvxdltefwq8tjlvne85tnp506ugj7z -p c=KCN,zap=KCN
```


[Mpool](https://api.mpool.live/wallet?ticker=KCN&address=kc1q5ed6nnk2jvxdltefwq8tjlvne85tnp506ugj7z)  
```sh
cpuminer-avx -a flex -o stratum+ssl://asia.mpool.live:5213 -u KCN=kc1q5ed6nnk2jvxdltefwq8tjlvne85tnp506ugj7z,LCN=lc1q8wcgexr6gzhxu3pmkecxtyj2htd5jaxmu3mpx3
```

## Stratum
US
```txt
stratum+ssl://us.mpool.live:5213
```
