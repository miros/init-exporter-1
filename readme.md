## `init-exporter`

Utility for exporting services described by Procfile to init system.

#### Installation

To build the init-exporter from scratch, make sure you have a working Go 1.5+ workspace ([instructions](https://golang.org/doc/install)), then:

```bash
git clone https://github.com/funbox/init-exporter.git --depth=1
cd init-exporter
make all
sudo make install
```

OR

```bash
go get github.com/funbox/init-exporter
sudo cp $GOPATH/bin/init-exporter /usr/sbin/
sudo cp $GOPATH/src/github.com/funbox/init-exporter/common/init-exporter.conf /etc/
```

#### Build Status

| Repository | Status |
|------------|--------|
| Stable | [![Build Status](https://travis-ci.org/funbox/init-exporter.svg?branch=master)](https://travis-ci.org/funbox/init-exporter) |
| Unstable | [![Build Status](https://travis-ci.org/funbox/init-exporter.svg?branch=develop)](https://travis-ci.org/funbox/init-exporter) |

#### License

init-exporter is released under the MIT license (see [LICENSE](LICENSE))
