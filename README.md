# videojs_localfiles

video.jsを用いたローカル動画ファイル再生用WEBページ。

## 起動方法

ローカルでのhtml起動の場合。

## serverフォルダ

お試しとしてDockerを用いて、apache httdサーバに該当ファイルを配置して実行できる構成を用意。
（htmlファイル自体は同一のものを利用）

## クローズド環境への対応

クローズド環境で外部インターネットへの通信が許容されていない環境の場合、*video.js*のライブラリをgithubからダウンロードしてくること。

```
    <link href=”http://vjs.zencdn.net/c/video-js.css" rel=”stylesheet”>
    <script src=”http://vjs.zencdn.net/c/video.js"></script>
```
