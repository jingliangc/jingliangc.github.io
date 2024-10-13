# [Jing Liang](https://github.com/HugoBlox/theme-academic-cv)

# Installation
[go](https://go.dev/doc/install)
```commandline
rm -rf /usr/local/go && tar -C /usr/local -xzf go1.23.2.linux-amd64.tar.gz
export PATH=$PATH:/usr/local/go/bin
go version
```
[SASS](https://sass-lang.com/install/) : download and add in path: 
```commandline
tar -C /usr/local -xzf dart-sass-1.79.4-linux-x64.tar.gz
export PATH="/usr/local/dart-sass:$PATH"
```
[hugo](https://github.com/gohugoio/hugo/releases): check the latest version
```commandline
wget https://github.com/gohugoio/hugo/releases/download/v0.135.0/hugo_extended_0.135.0_linux-amd64.deb
sudo dpkg -i hugo_extended_0.135.0_linux-amd64.deb
```

# Debug in local:
To show the website in local, we need to set content/.../xx.md: draft = false/true multiple times with restarting the "hugo server/hugo server -D"

### for the released version, set "content/.../xx.md: draft = false"
