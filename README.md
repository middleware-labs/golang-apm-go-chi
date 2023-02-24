# otelchi

[![ci](https://github.com/riandyrn/otelchi/actions/workflows/ci.yaml/badge.svg)](https://github.com/riandyrn/otelchi/actions/workflows/ci.yaml)
[![Go Report Card](https://goreportcard.com/badge/github.com/riandyrn/otelchi)](https://goreportcard.com/report/github.com/riandyrn/otelchi)
[![Documentation](https://godoc.org/github.com/riandyrn/otelchi?status.svg)](https://pkg.go.dev/mod/github.com/riandyrn/otelchi)

OpenTelemetry instrumentation for [go-chi/chi](https://github.com/go-chi/chi).

Essentialy this is adaptation from [otelmux](https://github.com/open-telemetry/opentelemetry-go-contrib/tree/main/instrumentation/github.com/gorilla/mux/otelmux) but instead using `gorilla/mux`, we use `go-chi/chi`.

Currently it could only instrument traces.

Contributions are welcomed!

## Install

```bash
$ go get github.com/middleware-labs/golang-apm-go-chi
```

## Examples

See [examples](./examples) for details.

## Why Port This?

I was planning to make this project as part of Open Telemetry Go instrumentation project. However based on [this comment](https://github.com/open-telemetry/opentelemetry-go-contrib/pull/986#issuecomment-941280855) they no longer accept new instrumentation. This is why I maintain this project here.
