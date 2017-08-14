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
blacktop/dbg        gef                 525MB
```

### Getting Started

```bash
$ docker run -d --name dbg --privileged --security-opt seccomp:unconfined blacktop/dbg
```

### Documentation

-	[voltron](docs/voltron.md)
-	[pwndbg](docs/pwndbg.md)
-	[gef](docs/gef.md)

### Known Issues :warning:

### Issues

Find a bug? Want more features? Find something missing in the documentation? Let me know! Please don't hesitate to [file an issue](https://github.com/blacktop/dbg/issues/new)

### Credits

### Todo

-	[ ] Add docs

### License

MIT Copyright (c) 2017 **blacktop**
