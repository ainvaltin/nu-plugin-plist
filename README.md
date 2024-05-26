# Nushell Plugin

[Nushell](https://www.nushell.sh/)
[Plugin](https://www.nushell.sh/contributor-book/plugins.html) 
written in [Go](https://go.dev/) using 
[nu-plugin package](github.com/ainvaltin/nu-plugin).

## Implements commands

- `to plist` and `from plist` - convert to and from [Property List](https://en.wikipedia.org/wiki/Property_list) format;
- `to base85` and `from base85` - encode and decode [ascii85 / base85](https://en.wikipedia.org/wiki/Ascii85) encoded data;

## Installation

Latest version is for Nushell version `0.93.0`.

To install it you need to have [Go installed](https://go.dev/dl/), then run
```sh
go install github.com/ainvaltin/nu-plugin-plist@latest
```
This creates the `nu_plugin_plist` binary in your `GOBIN` directory:
```txt
Executables are installed in the directory named by the GOBIN environment
variable, which defaults to $GOPATH/bin or $HOME/go/bin if the GOPATH
environment variable is not set.
```

Locate the binary and follow instructions on 
[Downloading and installing a plugin](https://www.nushell.sh/book/plugins.html#downloading-and-installing-a-plugin)
page on how to register `nu_plugin_plist` as a plugin.
