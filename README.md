# videojs_localfiles

video.jsを用いたローカル動画ファイル再生用WEBページ。

## 起動方法

ローカルでのhtml起動。

## serverフォルダ

お試しとしてDockerを用いて、apache httdサーバに該当ファイルを配置して実行できる構成を用意。
（htmlファイル自体は同一のものを利用）
WEB画面上でローカルファイルの再生が可能。

## クローズド環境への対応

クローズド環境で外部インターネットへの通信が許容されていない環境の場合、*video.js*のライブラリをgithubからダウンロードする必要あり。

```html
    <link href=”http://vjs.zencdn.net/c/video-js.css" rel=”stylesheet”>
    <script src=”http://vjs.zencdn.net/c/video.js"></script>
```

## 参考

- video.js公式

https://videojs.com/guides/embeds/

- video.js github

https://github.com/videojs/video.js
