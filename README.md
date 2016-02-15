CURIParser
==========

[![Swift 2.2](https://img.shields.io/badge/Swift-2.2-orange.svg?style=flat)](https://developer.apple.com/swift/)
[![Platforms Linux](https://img.shields.io/badge/Platforms-Linux-lightgray.svg?style=flat)](https://developer.apple.com/swift/)
[![License MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](https://tldrlegal.com/license/mit-license)
[![Slack Status](https://zewo-slackin.herokuapp.com/badge.svg)](http://slack.zewo.io)

**CURIParser** is an URI ([RFC 3986](https://tools.ietf.org/html/rfc3986)) parser for **Swift 2.2**.

## Installation

- Install [`uri_parser`](https://github.com/Zewo/uri_parser)

### Homebrew
```bash
$ brew tap zewo/tap
$ brew install uri_parser
```

### Ubuntu/Debian
```bash
$ echo "deb [trusted=yes] http://apt.zewo.io/deb ./" | sudo tee --append /etc/apt/sources.list
$ sudo apt-get update
$ sudo apt-get install uri_parser
```

### Source
```bash
$ git clone https://github.com/Zewo/uri_parser.git && cd uri_parser
$ make
$ (sudo) make install
```

- Add `CURIParser` to your `Package.swift`

```swift
import PackageDescription

let package = Package(
	dependencies: [
		.Package(url: "https://github.com/Zewo/CURIParser.git", majorVersion: 0, minor: 2)
	]
)

```

## Community

[![Slack](http://s13.postimg.org/ybwy92ktf/Slack.png)](https://zewo-slackin.herokuapp.com)

Join us on [Slack](https://zewo-slackin.herokuapp.com).

License
-------

**CURIParser** is released under the MIT license. See LICENSE for details.
