# article_15363_kobe_night_view

日本発の衛星データプラットフォーム Tellus のオウンドメディア「宙畑」の記事、https://sorabatake.jp/15363 で利用しているコードです。

観測点と指定した範囲の建物の見通しを判定し、判定結果をGeoJSONで返します。

## 構成
- los-check.ipynb
  - 見通しを判定するコード。
- example.pbf
  - 対象の範囲を指定するサンプルデータ。OpenStreetMapから取得。


## ライセンス、利用規約
ソースコードのライセンスは CC0-1.0（Creative Commons Zero v1.0 Universal）ライセンスです。  
今回コード内で ASTER GDEM2 データを用いております。利用ポリシーは以下をご参考下さい。
https://www.tellusxdp.com/market/tool_detail/tellus-default/60

## 貢献方法
プルリクエストや Issue はいつでも歓迎します。
