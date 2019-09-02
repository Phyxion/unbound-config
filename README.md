# unbound-config
configuration file for unbound recursive dns resolver


## Usage
* Install dependencies
```
apt-get install unbound libevent-dev
```

* Backup existing environment files
```
cd ~
mkdir .backup
sudo cp ~/.backup /etc/unbound/unbound.conf.d/*.conf
sudo rm /etc/unbound/unbound.conf.d/pi-hole.conf
```
* Clone the repository:
```
cd /etc/unbound/unbound.conf.d/
sudo wget https://raw.githubusercontent.com/saint-lascivious/unbound-config/master/unbound.conf
```

* Restart unbound
```sudo service unbound restart```

## Contact
* Discord
[SaintLascivious](https://discord.gg/9Cq4gRg)

* Email
saint.lascivious@gmail.com

* IRC
[##saint-lascivious](https://webchat.freenode.net/##saint-lascivious)

* Reddit
[saint-lascivious](https://www.reddit.com/user/saint-lascivious)

![alt text][logo]

[logo]:https://vignette.wikia.nocookie.net/pokemon/images/7/76/265Wurmple.png "Using the spikes on its rear end, Wurmple peels the bark off trees and feeds on the sap that oozes out. This Pokémon's feet are tipped with suction pads that allow it to cling to glass without slipping."
