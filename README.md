[![Tests](https://github.com/belluikit/glfw-js/actions/workflows/tests.yml/badge.svg)](https://github.com/belluikit/glfw-js/actions/workflows/tests.yml)
[![Static Analysis](https://github.com/belluikit/glfw-js/actions/workflows/analysis.yml/badge.svg)](https://github.com/belluikit/glfw-js/actions/workflows/analysis.yml)
[![Go Reference](https://pkg.go.dev/badge/github.com/belluikit/glfw-js.svg)](https://pkg.go.dev/github.com/belluikit/glfw-js)

# glfw-js

**Fork of [fyne-io/glfw-js](https://github.com/fyne-io/glfw-js)**, itself a
fork of [goxjs/glfw](https://github.com/goxjs/glfw) by Dmitri Shuralyov,
maintained for [Bellui](https://bellui.com)
([belluikit/bellui](https://github.com/belluikit/bellui)). The module path is
`github.com/belluikit/glfw-js`. On the browser backend this fork lets a window
be created without a WebGL context (`WindowHint(ClientAPI, NoAPI)`) and exposes
its canvas (`Window.GetCanvas`) so it can host WebGPU, plus input fixes. It remains under the original
[MIT License](LICENSE).

Package glfw experimentally provides a glfw-like API
with desktop (via glfw) and browser (via HTML5 canvas) backends.

It is used for creating a GL context and receiving events.

**Note:** This package is currently in development. The API is incomplete and may change.

## Installation

```sh
go get github.com/belluikit/glfw-js
```

## Directories

| Path                                                                | Synopsis                                                           |
|---------------------------------------------------------------------|--------------------------------------------------------------------|
| [test/events](https://pkg.go.dev/github.com/belluikit/glfw-js/test/events) | events hooks every available callback and outputs their arguments. |

## License

-	[MIT License](LICENSE)
