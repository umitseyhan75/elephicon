![preview](https://user-images.githubusercontent.com/52094761/83580862-1a0dec00-a578-11ea-8f37-2d9944733384.png)

[![GitHub CI](https://github.com/sprout2000/elephicon/workflows/GitHub%20CI/badge.svg)](https://github.com/sprout2000/elephicon/actions?query=workflow%3A%22GitHub+CI%22)
[![GitHub license](https://img.shields.io/github/license/sprout2000/elephicon)](https://github.com/sprout2000/elephicon/blob/master/LICENSE.md)
![GitHub package.json dynamic](https://img.shields.io/github/package-json/keywords/sprout2000/elephicon)

**Elephicon** (GUI Wrapper for [png2icons](https://github.com/idesis-gmbh/png2icons)) **generates [Apple ICNS](https://en.wikipedia.org/wiki/Apple_Icon_Image_format) and [Microsoft ICO](https://en.wikipedia.org/wiki/ICO_(file_format)) files from PNG files.**

## Usage

The ideal input is a 24 bit *PNG* with an alpha channel (RGBA) with *1024×1024* pixels but any other dimensions and most other PNG formats do also work. 

If you only need to create ICO files *256×256* pixels are sufficient. 

![result06](https://user-images.githubusercontent.com/52094761/83374029-50772a00-a405-11ea-897b-bba19e439b0c.gif)

You can also configure the settings by `right-click` context menu.

## Embedded Sizes

| Dimension | ICO | ICNS |
| :--- | :---: | :---: |
| 16x16 | ✅ | ✅ |
| 16x16@2x | | ✅ |
| 24x24 | ✅ | |
| 32x32 | ✅ | ✅ |
| 32x32@2x | | ✅ |
| 48x48 | ✅ | |
| 64x64 | ✅ | |
| 72x72 | ✅ | |
| 96x96 | ✅ | |
| 128x128 | ✅ | ✅ |
| 128x128@2x | | ✅ |
| 256x256 | ✅ | ✅ |
| 256x256@2x | | ✅ |
| 512x512 | | ✅ |
| 512x512@2x | | ✅ |

## Build & Install

```
$ git clone git@github.com:sprout2000/elephicon.git
$ cd elephicon
$ yarn install && yarn package
```

You will find the installer in `release` directory.

*Note that you will need to have [Node.js](https://nodejs.org/en/), [Git](https://git-scm.com/) and [Yarn](https://yarnpkg.com/) installed.*

## Download


### macOS

You can download the latest version of *Elephicon* from the releases page here:  
[https://github.com/sprout2000/elephicon/releases](https://github.com/sprout2000/elephicon/releases)

### Windows10

Download the latest version for Windows10 at [Microsoft Store](https://www.microsoft.com/store/apps/9P1489W92ZDQ).

## Security

API | Boolean
:--- | :---
nodeIntegration | `false`
enableRemoteModule | `false`
contextIsolation | `true`
safeDialogs | `true`
sandbox | `true`

## License

### [png2icons](https://github.com/idesis-gmbh/png2icons)

MIT © [idesis GmbH](https://www.idesis.de), Rellinghauser Straße 334F, D-45136 Essen

### Elephicon

[MIT](https://github.com/sprout2000/lessview/blob/master/LICENSE.md) © sprout2000
