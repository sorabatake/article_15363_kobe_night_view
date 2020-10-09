# article_15363_kobe_night_view

日本発の衛星データプラットフォーム Tellus のオウンドメディア「宙畑」の記事、[【Tellusで検証】神戸の夜景は本当に100万ドルか衛星データで検証してみた](https://sorabatake.jp/xxxxx/)
で利用しているコードです。

観測点と指定した範囲の建物の見通しを判定し、判定結果をGeoJSONで返します。

## 構成
- los-check.ipynb
  - 見通しを判定するコード。
- example.pbf
  - 対象の範囲を指定するサンプルデータ。OpenStreetMapから取得。


## ライセンス、利用規約
ソースコードのライセンスは MIT ライセンスです。  
取得した2次成果物の利用は基本的に、自由にコピー・配布いただけます。詳しくは以下をご参考下さい。
https://www.tellusxdp.com/docs/secondary-product.pdf

## 貢献方法
プルリクエストや Issue はいつでも歓迎します。
