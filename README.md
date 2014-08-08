# [BoxCI](http://boxci.io) Puppet Cassandra Module

This is a Puppet module that provides the open source Apache Cassandra 2.0 service.

### Intent

It is intended to be used by [BoxCI](http://boxci.io) but it can be used as a
normal Puppet module in general.

Being a [BoxCI](http://boxci.io) service module this service is configured so
that it is accessible from both inside the Guest (VM) as well as from the Host
machine.

### Supported OS

*Note:* This module currently only supports Ubuntu as currently
[BoxCI](http://boxci.io) supports Ubuntu images.

## Usage

To use this class simply declare it as follows:

```puppet
include cassandra
```

## Contribute

We welcome contributions. If you would like to contribute follow the steps
below.

1. Fork the repo
2. Make a topic branch
3. Make your changes
4. Submit a pull request
