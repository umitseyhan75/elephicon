# ![icon64](https://user-images.githubusercontent.com/52094761/80297794-80f1f580-87c1-11ea-9726-39fa0efe9581.png) GenICNS

ICNS Generator (GUI Wrapper for [idesis-gmbh/png2icons](https://github.com/idesis-gmbh/png2icons))

[![GitHub CI](https://github.com/sprout2000/gen-icns/workflows/GitHub%20CI/badge.svg)](https://github.com/sprout2000/gen-icns/actions?query=workflow%3A%22GitHub+CI%22)
[![GitHub license](https://img.shields.io/github/license/sprout2000/gen-icns)](https://github.com/sprout2000/gen-icns/blob/master/LICENSE.md)
![GitHub package.json dynamic](https://img.shields.io/github/package-json/keywords/sprout2000/gen-icns)

<img width="512" alt="2020-04-27 9 04 44" src="https://user-images.githubusercontent.com/52094761/80323428-51e18f80-8866-11ea-9f93-aedd454bbc18.png">


## Usage

Drop a PNG file to the window.

The ideal input is a 24 bit PNG with an alpha channel (RGBA) with 1024×1024 pixels but any other dimensions and most other PNG formats do also work. 

## Security

API | Boolean
:--- | :---
nodeIntegration | `false`
enableRemoteModule | `false`
contextIsolation | `true`
safeDialogs | `true`
sandbox | `true`

## Build and Install

Clone this repo

```
$ git clone git@github.com:sprout2000/gen-icns.git
```

Install the dependencies...

```
$ cd gen-icns
$ npm install
```

...then start to build the installer

```
$ npm run package
```

And you'll find the intaller in `release` directory.

## Download

You can download binary packages for macOS (signed & notarized) at [releases](https://github.com/sprout2000/gen-icns/releases).


## License

### [png2icons](https://github.com/idesis-gmbh/png2icons)

MIT © [idesis GmbH](https://www.idesis.de), Rellinghauser Straße 334F, D-45136 Essen

### GenICNS

[MIT](https://github.com/sprout2000/lessview/blob/master/LICENSE.md) © Office Nishigami