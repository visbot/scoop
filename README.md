# @visbot/scoop

:rotating_light:  *this repo is work in progress*

VISBOT manifests for [Scoop](https://scoop.sh), the Windows command-line installer.

## Prerequisites

Make sure that you have installed Winamp with Scoop, otherwise installing VISBOT releases won't work.

**Example**

```powershell
scoop bucket add naderi_scoop-bucket https://github.com/naderi/scoop-bucket
scoop install winamp
```

Note that there are several third-party [Winamp manifests](https://scoop.sh/#/apps?q=winamp) to choose from, others might work better for you!

## Installation

To add this bucket, run the following in your PowerShell:

```ps1
scoop bucket add visbot https://github.com/visbot/scoop
```

You can now install any VISBOT release using its catalogue number `scoop install visbot/<catalogue>`.

**Example**

```powershell
scoop install visbot/vc001
```

:warning: Catalogue numbers are case-sensitive, so make sure you type them all lowercase!

## Known Issues

- font installation is currently unsupported
- file names with Unicode characters might cause trouble
