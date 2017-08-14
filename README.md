dbg
===

[![Circle CI](https://circleci.com/gh/blacktop/dbg.png?style=shield)](https://circleci.com/gh/blacktop/dbg)
[![License](http://img.shields.io/:license-mit-blue.svg)](http://doge.mit-license.org)
[![Docker Stars](https://img.shields.io/docker/stars/blacktop/dbg.svg)](https://store.docker.com/community/images/blacktop/dbg)
[![Docker Pulls](https://img.shields.io/docker/pulls/blacktop/dbg.svg)](https://store.docker.com/community/images/blacktop/dbg)

> Docker `gdb`/`lldb` images
___

### Dependencies

-	[ubuntu:xenial (*118 MB*\)](https://hub.docker.com/_/ubuntu/)

### Image Tags

```bash
$ docker images

REPOSITORY          TAG                 VIRTUAL SIZE
blacktop/dbg        voltron             403MB
blacktop/dbg        pwndbg              568MB
blacktop/dbg        peda                299MB
blacktop/dbg        gef                 304MB
```

### Getting Started

```bash
$ docker run -ti --rm \
             --privileged \
             --name voltron \
             --volume `pwd`:/samples \
             --security-opt seccomp:unconfined \
             blacktop/dbg:voltron
```

> :warning: **NOTE:** you should normally never run docker in this way *(removing all the security features)*, but it is necessary for debugging

### Documentation

-	[voltron](docs/voltron.md)
-	[pwndbg](docs/pwndbg.md)
-	[peda](docs/peda.md)
-	[gef](docs/gef.md)

### Known Issues

### Issues

Find a bug? Want more features? Find something missing in the documentation? Let me know! Please don't hesitate to [file an issue](https://github.com/blacktop/dbg/issues/new)

### Todo

-	[ ] Add docs

### License

MIT Copyright (c) 2017 **blacktop**
