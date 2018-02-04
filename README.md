# Monstrator
URL shortening Telegram bot and libary
## Telegram bot
### Building
Monstrator doesn't have any dependencies. See the [documentation](https://golang.org/doc/install) on installing Go.
### Configuration
JSON and environment variables, which take precedence, are supported. The path to the JSON configuration file can be specified with the `-c` command line flag. See [this file](telegram/config.go) for all options.
## Libary [![GoDoc](https://godoc.org/github.com/r3turnz/monstrator?status.svg)](https://godoc.org/github.com/r3turnz/monstrator)
Monstrator's shortener abstraction is well documented and ready for use in other projects.
