> **Patched fork** of [extrame/ole2](https://github.com/extrame/ole2): corrupt sector chains return
> `ErrCorruptChain` instead of calling `log.Fatal` or reading forever. See [PATCHES.md](PATCHES.md) and
> upstream PR [#6](https://github.com/extrame/ole2/pull/6). Use together with
> [AntoniKwok/xls](https://github.com/AntoniKwok/xls) via `replace` directives.

# ole2
Microsoft Compound Document File Format library in Golang
