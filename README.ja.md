# Cesium

CesiumJSは、プラグインなしでウェブブラウザ上に世界最高レベルの3D地球儀や2Dマップを作成するためのJavaScriptライブラリです。ハードウェアアクセラレーションによるグラフィックスにWebGLを使用しており、クロスプラットフォームかつクロスブラウザ対応で、動的なデータの可視化に最適化されています。

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


[**Sandcastle ライブデモ**](https://sandcastle.cesium.com/) | [**ドキュメント**](https://cesium.com/learn/) | [**コミュニティフォーラム**](https://community.cesium.com/)

## 機能

- Cesium ionやその他のソースから、3D Tiles、画像データ、その他の標準フォーマットをストリーミングします。
- 高精度なWGS84の地球儀上でデータを可視化および分析します。
- パフォーマンス、精度、および時系列に沿った動的な可視化のために設計されています。
- デスクトップとモバイルをサポートし、クロスプラットフォームおよびクロスブラウザに対応しています。

すべての機能の一覧については、[CesiumJS Features Checklist](https://github.com/CesiumGS/cesium/wiki/CesiumJS-Features-Checklist)を参照してください。

## はじめに

### 前提条件

- WebGL2をサポートしているブラウザ。
- 開発サーバーには [Node.js](http://nodejs.org/) 16.x 以上が必要です。

### インストール

Webpack、Rollup、Parcelなどのモジュールバンドラーを使用するアプリケーションの場合、npmから `cesium` パッケージをインストールします:

```sh
npm install cesium --save
```

その後、必要なコンポーネントとCSSをアプリケーションにインポートします:

```js
import { Viewer } from "cesium";
import "cesium/Build/Cesium/Widgets/widgets.css";

const viewer = new Viewer("cesiumContainer");
```

詳細な手順やその他のインストール方法については、[CesiumJS Quickstart Guide](https://cesium.com/learn/cesiumjs-learn/cesiumjs-quickstart/)を参照してください。また、[ビルド済みのリリース](https://cesium.com/downloads/)のCesiumJSをダウンロードすることも可能です。

## コントリビューション

コミュニティからのコントリビューションを歓迎します！

- 質問がある場合は、[コミュニティフォーラム](https://community.cesium.com/)でご質問ください。
- コントリビューションにご興味がある場合は、開発者ガイドとベストプラクティスについて [CONTRIBUTING.md](CONTRIBUTING.md) を参照してください。

## ライセンス

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)。CesiumJSは商用・非商用を問わず無料で利用できます。
