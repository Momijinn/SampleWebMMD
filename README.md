# SampleWebMMD
Three.js ver_r106にてMMDを喋らせる自己的なサンプルプログラム

## Description
Webアプリケーション上で、[Three.js ver.r106](https://threejs.org/)を用いて[プロ生ちゃん](https://kei.pronama.jp/)を動かしてみるサンプルプログラム

## Demo
<a href="https://t.co/1HelNKNOaf">pic.twitter.com/1HelNKNOaf</a>

![capture](https://user-images.githubusercontent.com/13119897/60520218-f9ae2f80-9d1f-11e9-8838-0c3fcb1ab723.JPG)

## Requirement
### 動作確認済みのブラウザ
* Chrome
* Microsoft Edge

### Three.js & MMD & ammo.js
```html
<script src="https://cdn.jsdelivr.net/gh/mrdoob/three.js@r106/build/three.js"></script>
<script src="https://cdn.jsdelivr.net/gh/mrdoob/three.js@r106/examples/js/libs/mmdparser.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/ammo.js@0.0.10/ammo.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/mrdoob/three.js@r106/examples/js/loaders/TGALoader.js"></script>
<script src="https://cdn.jsdelivr.net/gh/mrdoob/three.js@r106/examples/js/loaders/MMDLoader.js"></script>
<script src="https://cdn.jsdelivr.net/gh/mrdoob/three.js@r106/examples/js/animation/MMDAnimationHelper.js"></script>
<script src="https://cdn.jsdelivr.net/gh/mrdoob/three.js@r106/examples/js/effects/OutlineEffect.js"></script>
<script src="https://cdn.jsdelivr.net/gh/mrdoob/three.js@r106/examples/js/animation/CCDIKSolver.js"></script>
<script src="https://cdn.jsdelivr.net/gh/mrdoob/three.js@r106/examples/js/animation/MMDPhysics.js"></script>
```

## Usage
```cmd
$ cd SampleWebMMD
$ live-server . # or other one liner web server
```

## Install
1. [プロ生ちゃんのPMXをダウンロード](https://3d.nicovideo.jp/works/td8608)し、pmx/puronama/ディレクトリにプロ生ちゃん.pmxが入っているディレクトリ内のファイルをすべて(png, bmp, pmx)いれる
2. [プロ生ちゃんのボイスデータ](https://onedrive.live.com/?id=623F2C273E554172%219450&cid=623F2C273E554172)をダウンロードし、audioディレクトリに __kei_voice_009_1.mp3__ と __kei_voice_010_2.mp3__ をいれる

## Licence
### Program
This software is released under the MIT License, see LICENSE.

### MMD & Voice
© 2019 合同会社プロ生

## Author
[Twitter](https://twitter.com/momijinn_aka)

[Blog](https://www.autumn-color.com/)