[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

# DynoV Open Metaverse Unity SDK

Package for DynoV Open Metaverse SDK.

- [How to use](#how-to-use)
- [Install](#install)
  - [via npm](#via-npm)
  - [via OpenUPM](#via-openupm)
  - [via Git URL](#via-git-url)
  - [Tests](#tests)
- [Configuration](#configuration)

<!-- toc -->

## How to use

*Work In Progress*

## Install

### via npm

Open `Packages/manifest.json` with your favorite text editor. Add a [scoped registry](https://docs.unity3d.com/Manual/upm-scoped.html) and following line to dependencies block:

```json
{
  "scopedRegistries": [
    {
      "name": "npmjs",
      "url": "https://registry.npmjs.org/",
      "scopes": [
        "com.Virtual-Dynamic-Labs"
      ]
    }
  ],
  "dependencies": {
    "com.Virtual-Dynamic-Labs.unity-dynov-open-metaverse-sdk": "1.0.0"
  }
}
```

Package should now appear in package manager.

### via OpenUPM

The package is also available on the [openupm registry](https://openupm.com/packages/com.Virtual-Dynamic-Labs.unity-dynov-open-metaverse-sdk). You can install it eg. via [openupm-cli](https://github.com/openupm/openupm-cli).

```
openupm add com.Virtual-Dynamic-Labs.unity-dynov-open-metaverse-sdk
```

### via Git URL

Open `Packages/manifest.json` with your favorite text editor. Add following line to the dependencies block:

```json
{
  "dependencies": {
    "com.Virtual-Dynamic-Labs.unity-dynov-open-metaverse-sdk": "https://github.com/Virtual-Dynamic-Labs/unity-dynov-open-metaverse-sdk.git"
  }
}
```

### Tests

The package can optionally be set as *testable*.
In practice this means that tests in the package will be visible in the [Unity Test Runner](https://docs.unity3d.com/2017.4/Documentation/Manual/testing-editortestsrunner.html).

Open `Packages/manifest.json` with your favorite text editor. Add following line **after** the dependencies block:

```json
{
  "dependencies": {
  },
  "testables": [ "com.Virtual-Dynamic-Labs.unity-dynov-open-metaverse-sdk" ]
}
```

## Configuration

*Work In Progress*

## License

MIT License

Copyright © 2022 Virtual Dynamic Labs
