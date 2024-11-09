# SML# package repositories

This is a collection of private package repositories maintained by
SML# project for several operating systems.

## Quick Start

To install the SML# compiler, run the following commands.

Debian sid:
```
wget -P /etc/apt/keyrings https://smlsharp.github.io/repos/debian/dists/sid/smlsharp-archive-keyring.gpg
wget -P /etc/apt/sources.list.d https://smlsharp.github.io/repos/debian/dists/sid/smlsharp.sources
apt update
apt install smlsharp
```

Debian 12 (bookworm):
```
wget -P /etc/apt/keyrings https://smlsharp.github.io/repos/debian/dists/bookworm/smlsharp-archive-keyring.gpg
wget -P /etc/apt/sources.list.d https://smlsharp.github.io/repos/debian/dists/bookworm/smlsharp.sources
apt update
apt install smlsharp
```

Debian 11 (bullseye):
```
wget -P /usr/share/keyrings https://smlsharp.github.io/repos/debian/dists/bullseye/smlsharp-archive-keyring.gpg
wget -P /etc/apt/sources.list.d https://smlsharp.github.io/repos/debian/dists/bullseye/smlsharp.list
apt update
apt install smlsharp
```

Fedora Rawhide:
```
rpm -i https://smlsharp.github.io/repos/fedora/smlsharp-release-fedora-41-1.noarch.rpm
dnf install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
```

AlmaLinux 9:
```
rpm -i https://smlsharp.github.io/repos/almalinux/smlsharp-release-almalinux-8-1.noarch.rpm
dnf install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
```

AlmaLinux 8:
```
rpm -i https://smlsharp.github.io/repos/almalinux/smlsharp-release-almalinux-8-1.noarch.rpm
dnf install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
```

During installation, you would be asked several times to confirm the
SML#'s public key. Its fingerprint is the following:
```
DD99 2B50 C9A3 B075 DA04 613A D299 F71F C5C1 D12E
```

For Ubuntu, we have a [PPA].

For macOS, see [homebrew-smlsharp].

[PPA]: https://launchpad.net/~smlsharp/+archive/ubuntu/ppa
[homebrew-smlsharp]: https://github.com/smlsharp/homebrew-smlsharp
