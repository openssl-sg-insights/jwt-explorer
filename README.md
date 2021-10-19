# JWT Explorer

A utility for inspecting, modifying, and attacking JWTs.

Supports Windows and Linux and probably also works on macOS but this has not been tested.

![Overview of JWT Explorer](images/overview.png)

## Usage

```bash
cargo run --release
```

Or download the latest release for your platform from [the releases page](https://github.com/sciguy16/jwt-explorer/releases)!

## Features

* Decode JWTs and inspect the headers and claims
* Automatically try some common secrets
* Generate `alg:none` attack payloads
* Easily update `iat` and `exp` with various offsets
* Sign and encode tokens with common algorithms
* Accept and encode invalid JSON payloads

## License

JWT Explorer is available under the terms of either the MIT license or
the Apache License (Version 2.0).

Fonts used are distributed under the terms of the Open Font License.

See [LICENSE-APACHE](LICENSE-APACHE), [LICENSE-MIT](LICENSE-MIT), and
fonts/\*/LICENSE for details.
