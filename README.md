# ports

Portfile collections for me.

# Usage

Get repository

```
$ git clone https://github.com/f110/ports.git
$ cd ports
$ portindex
```

Update sources.conf

```
$ vi /opt/local/etc/macports/sources.conf
file:///path/to/ports
rsync://rsync.macports.org/macports/release/tarballs/ports.tar [default]
```

Some ports is override to default port. Hence, You should add a line above the default.
