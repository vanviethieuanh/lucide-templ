# lucide Templ Icons

[![release](https://img.shields.io/github/release/vanviethieuanh/lucide-templ)](https://github.com/vanviethieuanh/lucide-templ/releases)
[![LICENSE](https://img.shields.io/badge/LICENCE-GPL3-red?style=flat)](./LICENSE)

This module provides all **lucide** icons as [templ](https://templ.guide) components.
Icons are generated automatically using [icon-forge](https://github.com/vanviethieuanh/icon-forge).

## Versioning

This commit using:

![Templ Version](https://img.shields.io/badge/templ-v0.3.960-blue)
![Icons](https://img.shields.io/badge/lucide-latest-orange)

## Installation

Tags format as: `v<lucide-version>-templ<templ-version>`.

So if you want to install
lucide version `0.0.1` which generated using templ version `0.0.2`,
then you likely want to install with tag `v0.0.1-templ0.0.2`.

Install the main branch, which is `latest` release of both templ and lucide using:

```bash
go get github.com/vanviethieuanh/lucide-templ
```

## Usage Example

```go
import "github.com/vanviethieuanh/lucide-templ"

templ SomeBiggerComponent(){
    @lucide_templ.ChevronFirst()
    @lucide_templ.X(lucide_templ.Props{Size: 20, StrokeWidth: 2})
}
```
