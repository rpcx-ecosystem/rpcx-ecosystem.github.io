## Welcome to RPCX

[rpcx 3.0](https://github.com/smallnest/rpcx/tree/v3.0) is coming!

[![License](https://img.shields.io/:license-apache-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![GoDoc](https://godoc.org/github.com/smallnest/rpcx?status.png)](http://godoc.org/github.com/smallnest/rpcx)  [![travis](https://travis-ci.org/smallnest/rpcx.svg?branch=v3.0)](https://travis-ci.org/smallnest/rpcx) [![Go Report Card](https://goreportcard.com/badge/github.com/smallnest/rpcx)](https://goreportcard.com/report/github.com/smallnest/rpcx) [![coveralls](https://coveralls.io/repos/smallnest/rpcx/badge.svg?branch=v3.0&service=github)](https://coveralls.io/github/smallnest/rpcx?branch=v3.0) [![QQ群](https://img.shields.io/:QQ群-398044387-blue.svg)](_documents/images/rpcx_qq.png)

**installation**

`go get -u -v github.com/smallnest/rpcx/...`


if you want to use quic/kcp, zookeeper, etcd, consul registry, use those tags. For example, if you want to use all, you can:

```
go get -u -v -tags "udp zookeeper etcd consul" github.com/smallnest/rpcx/...
```


rpcx is a distributed RPC framework like [Alibaba Dubbo](http://dubbo.io/) and [Weibo Motan](https://github.com/weibocom/motan).

**rpcx 3.0** has been refactored for:
1. **Simple**: use in 10 lines, raw go methods
2. **Performance**: high perforamnce (>= grpc-go)
3. **Cross-platform**: support _raw slice of bytes_, _JSON_, _Protobuf_ and _protobuf_. So it can be use in java, php, python, c/c++, node.js, c# and other platforms theoretically
4. **Service governance.**: support zookeeper, etcd and consul.

