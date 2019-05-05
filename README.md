# About

Command line tool to validate and pretty-print XML syntax of input
files.


## Installation

Windows and macOS binaries are available under [Releases](https://github.com/martinlindhe/validxml/releases)

Or install from source:

    go get -u github.com/martinlindhe/validxml


## Usage

Exit code will be 0 if file is good.

    $ validxml file.xml
    OK: file.xml

    $ curl http://site.com/file.xml | validxml
    OK: -


## Pretty-print

    $ validxml -p file.xml

XXX


## License

Under [MIT](LICENSE)
