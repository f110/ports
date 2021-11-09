# ports

Portfile collections for me.

# Usage

First time, You need to clone the repository and edit the config file for macports.
After the second time, You only need to sync it.

Clone the repository.

```
$ git clone https://github.com/f110/ports.git
```

Add this repository to /opt/local/macports/sources.conf

```
$ vi /opt/local/etc/macports/sources.conf
file:///path/to/ports
rsync://rsync.macports.org/macports/release/tarballs/ports.tar [default]
```

Some ports is override to default port. Hence, You should add a line above the default.
