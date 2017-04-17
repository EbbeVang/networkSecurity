# networkSecurity
## I2P (Invisible Internet Project)
### Install notes
Installed on Debian Jessie server:

install Java:
```bash
apt-get install default-jre
```

```bash
echo "deb https://deb.i2p2.de/ jessie main" >> /etc/apt/sources.list
echo "deb-src https://deb.i2p2.de/ jessie main" >> /etc/apt/sources.list
apt-key add i2p-debian-repo.key.asc
apt-get update
apt-get install i2p i2p-keyring
```

### references:
* https://wiki.debian.org/I2P
* https://wiki.debian.org/Java#JRE
* https://geti2p.net/en/

* https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
