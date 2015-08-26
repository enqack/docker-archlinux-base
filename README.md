# docker-archlinux-base

Another custom Arch Linux base container

* Github [enqack/docker-archlinux-base](https://github.com/enqack/archlinux-tiny)
* Docker hub [enqack/archlinux-base](https://hub.docker.com/r/enqack/archlinux-tiny)

Derivative of the [yantis/archlinux-tiny](https://hub.docker.com/r/yantis/archlinux-tiny) container.

## Features 
* Arch Linux 64 bit core, extra, community repos
* Arch Linux 32 bit multilib repo
* [Arch Linux CN](https://github.com/archlinuxcn) repo 
* user:docker password:docker
* [Reflector] (https://wiki.archlinux.org/index.php/Reflector) mirror optimized for western USA.
* cower and package-query for interacting with the AUR. 
* compact (removal of a lot of unneeded stuff that pacman will auto re-install if needed)

## packages

* acl 2.2.52-2
* archlinux-keyring 20150605-1
* archlinuxcn-keyring 20150516-1
* attr 2.4.47-1
* bash 4.3.039-1
* bzip2 1.0.6-5
* ca-certificates 20150402-1
* ca-certificates-cacert 20140824-2
* ca-certificates-mozilla 3.19.2-2
* ca-certificates-utils 20150402-1
* coreutils 8.24-1
* cower 13-1
* curl 7.43.0-1
* e2fsprogs 1.42.12-2
* expat 2.1.0-4
* filesystem 2015.02-1
* findutils 4.4.2-6
* gawk 4.1.3-1
* gcc-libs 5.2.0-2
* glibc 2.22-1
* gmp 6.0.0-2
* gnupg 2.1.7-1
* gnutls 3.4.4.1-1
* gpgme 1.5.5-1
* grep 2.21-2
* gzip 1.6-1
* iana-etc 2.30-5
* keyutils 1.5.9-1
* krb5 1.13.2-1
* less 479-1
* libarchive 3.1.2-8
* libassuan 2.2.1-1
* libcap 2.24-2
* libffi 3.2.1-1
* libgcrypt 1.6.3-2
* libgpg-error 1.19-1
* libidn 1.32-1
* libksba 1.3.3-1
* libldap 2.4.42-1
* libsasl 2.1.26-7
* libssh2 1.6.0-1
* libtasn1 4.5-1
* libutil-linux 2.26.2-1
* licenses 20140629-1
* linux-api-headers 4.1.4-1
* localepurge 0.7.3.4-1
* lzo 2.09-1
* mpfr 3.1.3.p4-1
* ncurses 5.9-7
* nettle 3.1.1-1
* npth 1.2-1
* openssl 1.0.2.d-1
* p11-kit 0.23.1-2
* package-query 1.6.2-1
* pacman 4.2.1-2
* pacman-mirrorlist 20150811-1
* pcre 8.37-3
* pinentry 0.9.5-1
* pth 2.0.7-5
* readline 6.3.008-1
* sed 4.2.2-3
* tar 1.28-1
* texinfo-fake 1.2-1
* tzdata 2015f-1
* wget 1.16.3-1
* which 2.21-1
* xz 5.2.1-1
* yajl 2.1.0-1
* zlib 1.2.8-4
