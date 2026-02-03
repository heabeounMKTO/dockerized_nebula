#install nebula
i assume u are using linux so you can install nebula from your package manager or releases

#initial setup (any of your local/remote machine)

- generate ca
```
nebula-cert ca -name "meshname" # provate and public keypair
nebula-cert sign -name "lighthouse" -ip "192.168.100.1/24"
nebula-cert sign -name "node1" -ip "192.168.100.2/24"
```
