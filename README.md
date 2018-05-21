# gochecknoglobals

[![Build Status](https://img.shields.io/travis/leighmcculloch/gochecknoglobals.svg)](https://travis-ci.org/leighmcculloch/gochecknoglobals)
[![Codecov](https://img.shields.io/codecov/c/github/leighmcculloch/gochecknoglobals.svg)](https://codecov.io/gh/leighmcculloch/gochecknoglobals)
[![Go Report Card](https://goreportcard.com/badge/github.com/leighmcculloch/gochecknoglobals)](https://goreportcard.com/report/github.com/leighmcculloch/gochecknoglobals)

Check that no globals are present in Go code.

## Why

Global variables are an input to functions that is not visible in the functions signature, complicate testing, reduces readability and increase the complexity of code.

https://peter.bourgon.org/blog/2017/06/09/theory-of-modern-go.html
https://twitter.com/davecheney/status/871939730761547776

## Install

```
go get 4d63.com/gochecknoglobals
```

## Usage

```
gochecknoglobals
```

or

```
gochecknoglobals [path] [path] ...
```
