# HUNTER x HUNTER 渋谷巡回ルート

## Files

- `index.html`: 現地用のスマホ最適化HTMLアプリ。Segment切替、各地点Google Maps起動、詳細アコーディオン、回収チェック、現在地からの最寄り強調に対応。
- `hxh_shibuya_route_guide.html`: `index.html` と同内容。旧ファイル名で開きたい場合はこちら。
- `hxh_shibuya_mobile_nav.md`: スマホ用のGoogle Maps区間リンク集。
- `hxh_shibuya_mymaps_mobile_optimized.csv`: Google My Maps向け最適化CSV。緯度経度指定 + タイトル先頭に順番/キャラ要約入り。
- `hxh_shibuya_mymaps_import.csv`: Google My Maps取り込み用。位置情報の列は `Address`、タイトル列は `Name`。
- `hxh_shibuya_google_maps_links.md`: Google Mapsで開ける4分割の徒歩ルートリンク。

## Recommended Use

1. 現地では `index.html` をスマホで開き、Segmentタブと回収チェックを使う。
2. 移動するときだけ、HTML内の「Googleマップ」ボタンか `hxh_shibuya_mobile_nav.md` のSegmentリンクを開く。
3. Google My Mapsにも入れる場合は `hxh_shibuya_mymaps_mobile_optimized.csv` を使う。位置情報は `Latitude` / `Longitude`、タイトルは `Name` を指定する。

Google Mapsの通常経路は立ち寄り数に上限があるため、31地点を4区間に分けています。
