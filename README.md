# Goth Generator for Buffalo

[![Standard Test](https://github.com/gobuffalo/buffalo-goth/actions/workflows/standard-go-test.yml/badge.svg)](https://github.com/gobuffalo/buffalo-goth/actions/workflows/standard-go-test.yml)
[![Go Reference](https://pkg.go.dev/badge/github.com/gobuffalo/buffalo-goth.svg)](https://pkg.go.dev/github.com/gobuffalo/buffalo-goth)
[![Go Report Card](https://goreportcard.com/badge/github.com/gobuffalo/buffalo-goth)](https://goreportcard.com/report/github.com/gobuffalo/buffalo-goth)

Buffalo-goth is a plugin for [buffalo cli](https://github.com/gobuffalo/cli)
that makes it easy to integrate [goth](https://github.com/markbates/goth)
into your Buffalo application.

In Buffalo `v0.9.4` the built in generator for [github.com/markbates/goth](https://github.com/markbates/goth) was removed in favor of this plugin.

## Installation

```console
$ buffalo plugins install github.com/gobuffalo/buffalo-goth@latest
```

## Usage

Generate Users, Routes

```console
$ buffalo generate goth-auth facebook twitter linkedin etc...
```

Generate Routes only

```console
$ buffalo generate goth facebook twitter linkedin etc...
```

For more detailed usage visit
https://gobuffalo.io/documentation/guides/goth/
