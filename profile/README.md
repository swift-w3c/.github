# Swift W3C

Swift implementations of W3C (World Wide Web Consortium) specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 2 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-w3c-<spec>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`W3C_SVG`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

> Swift W3C is an independent open-source project. It is not affiliated with, endorsed by, or sponsored by the World Wide Web Consortium.

## Coverage

| Package | Specification |
|---|---|
| [swift-w3c-css](https://github.com/swift-w3c/swift-w3c-css) | Cascading Style Sheets (CSS) |
| [swift-w3c-cssom](https://github.com/swift-w3c/swift-w3c-cssom) | CSS Object Model (CSSOM) |
| [swift-w3c-svg](https://github.com/swift-w3c/swift-w3c-svg) | Scalable Vector Graphics 2 |
| [swift-w3c-xml](https://github.com/swift-w3c/swift-w3c-xml) | Extensible Markup Language (XML) |
| [swift-w3c-png](https://github.com/swift-w3c/swift-w3c-png) | Portable Network Graphics (PNG) |
| [swift-w3c-epub](https://github.com/swift-w3c/swift-w3c-epub) | EPUB 3.3 |

Every repository description carries the specification's full title; the [repositories tab](https://github.com/orgs/swift-w3c/repositories) lists them all.

## Status

Public alpha. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
