gRPC demo with Gob codec (Go)
======================

PREREQUISITES
-------------

- This requires Go 1.7 or later
- Requires that [GOPATH is set](https://golang.org/doc/code.html#GOPATH)

```
$ go help gopath
$ # ensure the PATH contains $GOPATH/bin
$ export PATH=$PATH:$GOPATH/bin
```

INSTALL
-------

```
$ go get -u github.com/harshavardhana/grpc-gob-hello/greeter_client
$ go get -u github.com/harshavardhana/grpc-gob-hello/greeter_server
```

TRY IT!
-------

- Run the server

```
$ greeter_server &
```

- Run the client

```
$ greeter_client
```
