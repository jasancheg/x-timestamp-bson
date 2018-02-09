# x-timestamp-bson

This mdoule allows you to create and parse BSON `Timestamp`s without a reference to the
[mongodb](https://github.com/mongodb/node-mongodb-native) or [bson](https://github.com/mongodb/js-bson)
modules.

It is just a mirrow of the [timestamp.js](https://github.com/mongodb/js-bson/blob/master/lib/bson/timestamp.js) file in [bson](https://github.com/mongodb/js-bson). Created for the x-db-oplog-cursor](https://github.com/jasancheg/x-db-oplog-cursor) project, where it is just needed to use the `Timestamp` class for a tiny conversion.

### Installation

```bash
$ npm install https://github.com/jasancheg/x-timestamp-bson
```

### Usage

Check the [official use guide](http://docs.mongodb.org/master/reference/bson-types/#timestamps).

### Build

``` bash
$ make build
```

### License

Apache v2.0

See LICENSE file.
