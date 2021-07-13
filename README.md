# openssl_ext

RSA C Bindings for Crystal (and other extensions)

## Installation

Add this to your application's `shard.yml`:

```yaml
dependencies:
  openssl_ext:
    github: toddsundsted/openssl_ext
```

## Usage

```crystal
require "openssl_ext"
```

See `spec/rsa_spec.cr` and `spec/x509_spec.cr` for usage in depth.
The bindings closely follows the API for https://ruby-doc.org/stdlib-2.4.0/libdoc/openssl/rdoc/OpenSSL/PKey/RSA.html

**Encoding with a passphrase is not yet supported as OpenSSL fails silently without any errors (in order to fix).**


## Contributors

- [cimrie](https://github.com/cimrie) Connor Imrie - creator, maintainer
