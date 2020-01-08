## 0.1.1

Mainly documentation and internal refactoring:

* Made `Encoder` and `Decoder` into interfaces with corresponding `StdEncoder` / `StdDecoder`.
* Removal of intermediate objects in `Codec`

## 0.1.0

Initial release version of XML-RPC client.

* Support for all XML-RPC types both encoding and decoding.
* A client implementation based on `net/rpc` for familiar interface.
* No external dependencies (except testing code dependencies)