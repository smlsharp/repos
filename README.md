# SML# package repositories

This is a collection of private package repositories maintained by
SML# project for several operating systems.

## Quick Start

To install the SML# compiler, run the following commands.

Debian sid:
```
wget -P /usr/share/keyrings https://github.com/smlsharp/repos/raw/main/debian/dists/sid/smlsharp-archive-keyring.gpg
wget -P /etc/apt/sources.list.d https://github.com/smlsharp/repos/raw/main/debian/dists/sid/smlsharp.list
apt update
apt install smlsharp
```

Debian 10 (buster):
```
wget -P /usr/share/keyrings https://github.com/smlsharp/repos/raw/main/debian/dists/buster/smlsharp-archive-keyring.gpg
wget -P /etc/apt/sources.list.d https://github.com/smlsharp/repos/raw/main/debian/dists/buster/smlsharp.list
apt update
apt install smlsharp
```

Fedora Rawhide:
```
rpm -i https://github.com/smlsharp/repos/raw/main/fedora/smlsharp-release-rawhide-31-1.noarch.rpm
dnf install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
```

Fedora:
```
rpm -i https://github.com/smlsharp/repos/raw/main/fedora/smlsharp-release-fedora-31-1.noarch.rpm
dnf install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
```

CentOS 8:
```
rpm -i https://github.com/smlsharp/repos/raw/main/centos/smlsharp-release-centos-8-1.noarch.rpm 
dnf install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
```

CentOS 7:
```
yum install epel-release
rpm -i https://github.com/smlsharp/repos/raw/main/centos/smlsharp-release-centos-7-1.noarch.rpm
yum install smlsharp smlsharp-smlformat smlsharp-smllex smlsharp-smlyacc
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
