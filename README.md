Micro editor debian package generator
=====================================

This script downloads the latest version of [Micro editor](https://micro-editor.github.io/)
and creates Debian package (.deb file).

Usage
-----

Download the script and execute it:

```bash
./micro-deb
```

It will create a deb file in the current directory.
You can install it with `dpkg`:

```bash
dpkg -i micro_<VERSION AND ARCHITECTURE>.deb
```

Restrictions
------------

The script supports only these architectures:

- linux32,
- linux64
- linux-arm.
