# Go-Enodo

A Go client lib for the [SiriDB Enodo Platform](https://github.com/SiriDB/siridb-enodo-hub)

---------------------------------------
  * [Installation](#installation)
  * [Usage](#usage)
  
---------------------------------------

## Installation
Simple install the package to your [$GOPATH](https://github.com/golang/go/wiki/GOPATH "GOPATH") with the [go tool](https://golang.org/cmd/go/ "go command") from shell:
```bash
$ go get github.com/SiriDB/siridb-enodo-go-lib
```
Make sure [Git is installed](https://git-scm.com/downloads) on your machine and in your system's `PATH`.

## Usage
`CreatePackage` can be used to create a new package with a given type, id and data. Returns value of type `[]byte`
`ReadHeaderFromBinaryData` can be used to read a header from a `[]byte`, func returns upcoming data length, package type and package ID
