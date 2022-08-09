```
git cmake ninja-build pkg-config clang lld binfmt-support libsdl2-dev libepoxy-dev g++-x86-64-linux-gnu nasm python3-clang  squashfs-tools squashfuse
```
 wget https://ryanfortner.github.io/box64-debs/box64.list -O /etc/apt/sources.list.d/box64.list \
wget -O- https://ryanfortner.github.io/box64-debs/KEY.gpg | gpg --dearmor | sudo tee /usr/share/keyrings/box64-debs-archive-keyring.gpg \
apt update && sudo apt install box64 -y
