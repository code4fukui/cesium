# Cesium

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

CesiumJS is a JavaScript library for creating world-class 3D globes and 2D maps in a web browser without a plugin. It uses WebGL for hardware-accelerated graphics, and is cross-platform, cross-browser, and tuned for dynamic-data visualization.

[
![Build Status](https://travis-ci.com/CesiumGS/cesium.svg?branch=main)
](https://travis-ci.com/CesiumGS/cesium)
[
![npm](https://img.shields.io/npm/v/cesium)
](https://www.npmjs.com/package/cesium)
[
![Docs](https://img.shields.io/badge/docs-online-orange.svg)
](https://cesium.com/learn/)


![Cesium](https://github.com/CesiumGS/cesium/wiki/logos/Cesium_Logo_Color.jpg)


[**Sandcastle Live Demos**](https://sandcastle.cesium.com/) | [**Documentation**](https://cesium.com/learn/) | [**Community Forum**](https://community.cesium.com/)

## Features

- Stream 3D Tiles, imagery, and other standard formats from Cesium ion or other sources.
- Visualize and analyze data on a high-precision WGS84 globe.
- Built for performance, precision, and time-dynamic visualization.
- Cross-platform and cross-browser, with support for desktop and mobile.

See the [CesiumJS Features Checklist](https://github.com/CesiumGS/cesium/wiki/CesiumJS-Features-Checklist) for a full list of features.

## Getting Started

### Prerequisites

- A browser that supports WebGL2.
- [Node.js](http://nodejs.org/) 16.x or newer is required for the development server.

### Installation

For applications using a module bundler like Webpack, Rollup, or Parcel, install the `cesium` package from npm:

```sh
npm install cesium --save
```

Then, import the necessary components and CSS into your application:

```js
import { Viewer } from "cesium";
import "cesium/Build/Cesium/Widgets/widgets.css";

const viewer = new Viewer("cesiumContainer");
```

For detailed instructions and other ways to install, see the [CesiumJS Quickstart Guide](https://cesium.com/learn/cesiumjs-learn/cesiumjs-quickstart/). You can also download a [pre-built release](https://cesium.com/downloads/) of CesiumJS.

## Contributing

We welcome contributions from the community!

- Have questions? Ask them on the [community forum](https://community.cesium.com/).
- Interested in contributing? See [CONTRIBUTING.md](CONTRIBUTING.md) for developer guides and best practices.

## License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html). CesiumJS is free for both commercial and non-commercial use.