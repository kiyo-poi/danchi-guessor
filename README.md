# Danchi Guessor（ダンチゲッサー）

団地の境界線当てゲーム。遊ぶ：https://kiyo-poi.github.io/danchi-guessor/

出題された町の境界を地図の上でクリックして囲み、本物とどれだけ重なるかで100点満点。1問3分。

出題エリア
- 鹿児島中心街（鹿児島中央駅から5km）
- 鹿児島市（市街地・住宅街・団地）
- 東京中心街（山手線の内側）
- 東京23区
- 大阪中心街（大阪環状線の内側）

データ
- 地図：OpenStreetMap（OpenFreeMap）。町名のラベルは消してあります
- 航空写真：国土地理院
- 町の境界：[Geolonia 領域データ](https://github.com/geolonia/japanese-boundaries)（平成27年国勢調査の町丁・字境界がもと。丁目はまとめて1つの町にしています）
- 山手線・大阪環状線の位置：国土数値情報（鉄道データ）をもとにした [Jinshin-visualization](https://github.com/yutyan0119/Jinshin-visualization)
