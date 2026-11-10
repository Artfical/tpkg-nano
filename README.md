# nano

GNU nano 9.3: a small, friendly text editor

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install nano
```

| | |
|---|---|
| Version | 9.3 |
| Licence | GPL-3.0+ |
| Upstream | https://www.nano-editor.org |
| Needs | [`terminfo`](https://github.com/Artfical/tpkg-terminfo) |
| Needs tOS build | 616 or newer |
| Size | 716015 bytes (1535158 unpacked) |
| SHA-256 of the `.tpkg` | `88bc2fbfd292fd4409187ff7096dc5e9bdb38232c743ba54dd284438f2e8bb01` |

## Commands it adds

| Command | Runs |
|---|---|
| `nano` | `bin/nano` |

## Download

The package file (`nano-9.3.tpkg`) and the sources it was built from are the assets of the
[v9.3 release](https://github.com/Artfical/tpkg-nano/releases/tag/v9.3).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `nano-9.3.tar.xz`
- `ncurses-6.5.tar.gz`

Check a download: `sha256sum nano-9.3.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0+. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
