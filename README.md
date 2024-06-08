```
apt update && apt install iptables ipset netfilter-persistent ipset-persistent nftables git -y && git clone https://github.com/dariring/antiddossans && cd antiddossans && bash antiddos-yuki && cd ..
```
```
sudo iptables-nft -P INPUT ACCEPT && sudo nft flush ruleset && sudo ipset destroy blacklist
```
