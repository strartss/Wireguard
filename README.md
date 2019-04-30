# Usage

Download
``` bash
wget https://raw.githubusercontent.com/jasminebd/Wireguard/master/wireguard_install_ubuntu_BD.sh
```

Run
``` bash
sh wireguard_install_ubuntu_BD.sh
```

Configuration file 
``` bash
/etc/wireguard/wg0.conf
```

Client Configuration File
``` bash
/etc/wireguard/client.conf
```

# Screenshots
![Screenshots](https://github.com/jasminebd/Wireguard/blob/master/Screenshots.png?raw=true)


Start Up WireGuard
``` bash
wg-quick up wg0
```

Stop WireGuard
``` bash
wg-quick down wg0
```

View WireGuard Operating status
``` bash
wg
```
