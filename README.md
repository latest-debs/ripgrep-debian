# ripgrep for Debian

[ripgrep](https://github.com/BurntSushi/ripgrep) — recursively searches directories for a regex pattern while respecting your gitignore — packaged for
Debian as part of [latest-debs](https://github.com/latest-debs).

## Install

Via the latest-debs apt repository:

```sh
sudo extrepo enable latest-debs
sudo apt update
sudo apt install ripgrep
```

Or download a `.deb` from the [Releases](https://github.com/latest-debs/ripgrep-debian/releases) page:

```sh
sudo dpkg -i ripgrep_*.deb
```

## Supported distributions & architectures

- Debian Bookworm (12), Trixie (13), Forky (14/testing), Sid (unstable)
- amd64, arm64, armhf, i386 (bookworm/trixie), ppc64el, riscv64, s390x

## Building

Run the [Build ripgrep for Debian](../../actions) workflow on GitHub with the
desired upstream version. Packaging is driven by
[debian-multiarch-builder](https://github.com/ranjithrajv/debian-multiarch-builder).

## Collaborate with us

latest-debs is a community effort. If you rely on this package and want to
help keep it fresh, watching for a new upstream release or fixing a build
hiccup, we'd love your help. Open an issue on this repo, or email
**latest-debs@users.noreply.github.com** to get involved.

## Disclaimer

Unofficial packaging only. For issues with ripgrep itself, see
[BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep).
