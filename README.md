# Scoop Bucket for Zam
![Zam Logo](assets/logo_banner.png)
Official [Scoop](https://scoop.sh) bucket for the **Zam** programming language.

## Installation

To install `zam` using Scoop on Windows, first add this bucket:

```powershell
scoop bucket add zam https://github.com/Zambozoo/scoop-zam
```
Then install the language:

```powerShell
scoop install zam
```

## Prerequisites
C Compiler (cc): Because zam invokes a C compiler during execution, we recommend installing GCC through Scoop if you haven't already:

```powerShell
scoop install gcc
```

## Verification
Once installed, verify the installation by checking the version:

```powerShell
zam --version
```

## Maintenance & Updates
To update zam and all your bucket packages to the latest release:

```powerShell
scoop update
scoop update zam
```

For issues, feature requests, or documentation regarding the language itself, please visit the [zam repository](https://github.com/Zambozoo/zam).