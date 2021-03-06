[![Build Status](https://travis-ci.com/intelsdi-x/snap-plugin-publisher-etcd.svg?token=T9mMhEjMRckyN65RdWFp&branch=master)](https://travis-ci.org/intelsdi-x/snap-plugin-publisher-etcd)


# snap publisher plugin - etcd

Allows publishing of data to [etcd](https://coreos.com/etcd/) from the [Snap framework](http://github.com:intelsdi-x/snap).

1. [Getting Started](#getting-started)
  * [System Requirements](#system-requirements)
  * [Installation](#installation)
  * [Configuration and Usage](configuration-and-usage)
2. [Documentation](#documentation)
  * [Roadmap](#roadmap)
3. [Community Support](#community-support)
4. [Contributing](#contributing)
5. [License](#license-and-authors)
6. [Acknowledgements](#acknowledgements)

## Getting Started
### System Requirements
* A running instance of etcd ([release page](https://github.com/coreos/etcd/releases/))
* [golang 1.5+](https://golang.org/dl/) (needed only for building)

### Operating systems
All OSs currently supported by snap:
* Linux/amd64
* Darwin/amd64

### Installation
#### Download etcd plugin binary:
You can get the pre-built binaries for your OS and architecture at snap's [GitHub Releases](https://github.com/intelsdi-x/snap/releases) page.

#### To build the plugin binary:
Fork https://github.com/intelsdi-x/snap-plugin-publisher-etcd
Clone repo into `$GOPATH/src/github.com/intelsdi-x/`:

```
$ git clone https://github.com/<yourGithubID>/snap-plugin-publisher-etcd.git
```

Build the plugin by running make within the cloned repo:
```
$ make
```
This builds the plugin in `/build/rootfs/`

### Configuration and Usage
* Set up the [Snap framework](https://github.com/intelsdi-x/snap/blob/master/README.md#getting-started)

## Documentation
There are a number of other resources you can review to learn to use this plugin:

* [etcd documentation](https://coreos.com/etcd/docs/latest/faq.html) 
* [etcd GitHub](https://github.com/coreos/etcd)

### Roadmap
There isn't a current roadmap for this plugin, but it is in active development. As we launch this plugin, we do not have any outstanding requirements for the next release. If you have a feature request, please add it as an [issue](https://github.com/intelsdi-x/snap-plugin-publisher-etcd/issues/new) and/or submit a [pull request](https://github.com/intelsdi-x/snap-plugin-publisher-etcd/pulls).

## Community Support
This repository is one of **many** plugins in **Snap**, a powerful telemetry framework. See the full project at http://github.com/intelsdi-x/snap To reach out to other users, head to the [main framework](https://github.com/intelsdi-x/snap#community-support)

## Contributing
We love contributions!

There's more than one way to give back, from examples to blogs to code updates. See our recommended process in [CONTRIBUTING.md](CONTRIBUTING.md).

## License
[snap](http://github.com:intelsdi-x/snap), along with this plugin, is an Open Source software released under the Apache 2.0 [License](LICENSE).

## Acknowledgements
* Author: [@kindermoumoute](https://github.com/kindermoumoute/)

And **thank you!** Your contribution, through code and participation, is incredibly important to us.
