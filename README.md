# Rd. Note road data

iOS アプリ「Rd. Note」の道路データ(走ったあとに道路へ当てはめるための Valhalla のタイルと、道路名・地点名のデータ)の配布元です。
ファイルは Releases に回ごとに置きます。アプリは、設定 → 道路データで利用者が地方を選んだときだけ取得します。

## ライセンス

- データ: © OpenStreetMap contributors
- このリポジトリで配布するデータは、OpenStreetMap のデータから作った派生データベースで、
  [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/) のもとで提供します。
- OpenStreetMap の著作権とライセンス: https://www.openstreetmap.org/copyright
- 各リリースに LICENSE.txt と README.txt(作り方)を同梱します。

## データの全体と作り方(ODbL 4.6)

どなたでも無料で受け取れます。

- 地方ごとの道路データ(Valhalla のタイル・その地方の道路名と地点名): `jp-car-*` のリリース(最新は [jp-car-20261026](https://github.com/winniecraftsoftware/rdnote-map-data/releases/tag/jp-car-20261026))
- アプリに同梱している道路名・地点名のデータ: [app-names-20261010](https://github.com/winniecraftsoftware/rdnote-map-data/releases/tag/app-names-20261010)

---

Road data for the iOS app Rd. Note: Valhalla tiles used to match a drive to roads afterwards, plus road and place names.
Files are published as Releases and are downloaded only when the user chooses a region in Settings → Road data.

Data © OpenStreetMap contributors, available under the Open Database License (ODbL) 1.0.
The entire Derivative Database and the method of alteration are available free of charge in the Releases above (ODbL 4.6).
