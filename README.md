# 概要

rocker/rstudioでは日本語フォントが使えないので、IPAフォントをインストールしたイメージを用意することにしました。

[rocker/rstudioイメージでplotを使うときに文字化けしないようにする](http://mao-instantlife.hatenablog.com/entry/2016/09/21/rocker/rstudio%E3%82%A4%E3%83%A1%E3%83%BC%E3%82%B8%E3%81%A7plot%E3%82%92%E4%BD%BF%E3%81%86%E3%81%A8%E3%81%8D%E3%81%AB%E6%96%87%E5%AD%97%E5%8C%96%E3%81%91%E3%81%97%E3%81%AA%E3%81%84%E3%82%88)

# 利用方法

rocker/rstudioと同じです。ポートをexposeして実行してください。

```
docker run -d -p 8787:8787 --name rstudio shinsukeabe/rstudio-with-ipafont
```
