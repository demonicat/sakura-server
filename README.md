# Sakura Server
![GitHub repo size](https://img.shields.io/github/repo-size/demonicat/sakura-server)
[![GitHub](https://img.shields.io/github/license/demonicat/sakura-server)](https://github.com/demonicat/sakura-server/blob/master/LICENSE)

Based on otland's forgottenserver 1.4.1

### Compiling on Arch Linux
Install deps:
```sh
sudo pacman -Syu base-devel git cmake luajit boost boost-libs libmariadbclient pugixml crypto++ fmt --needed
```

Get the code:
```sh
git clone https://github.com/demonicat/sakura-server.git
```

Compile:
```sh
cd sakura-server
cmake . -B build
make -C build -j$(nproc)
```