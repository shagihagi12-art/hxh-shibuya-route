# HXH渋谷巡回ナビをXで拡散して誰でも使えるようにする手順

公開URL: https://shagihagi12-art.github.io/hxh-shibuya-route/

## 最短のおすすめ

GitHub Pagesで公開するのが一番わかりやすいです。公開後のURLをXに貼れば、誰でもスマホで `index.html` を開いて使えます。

## GitHub Pagesで公開

1. GitHubで新しいPublicリポジトリを作る
   - 例: `hxh-shibuya-route`
2. このフォルダ内のファイルをアップロードする
   - 必須: `index.html`
   - あると便利: `hxh_shibuya_mobile_nav.md`, `hxh_shibuya_mymaps_mobile_optimized.csv`, `README.md`
3. GitHubのリポジトリ画面で `Settings` -> `Pages`
4. `Build and deployment` で `Deploy from a branch`
5. Branchを `main`、folderを `/root` にして保存
6. 数十秒後に表示されるURLを開く
   - 例: `https://ユーザー名.github.io/hxh-shibuya-route/`

## Cloudflare Pagesで公開

1. Cloudflare Pagesで新規プロジェクトを作る
2. GitHubリポジトリを接続する
3. Framework presetは指定なし
4. Build commandは空
5. Output directoryは `/`
6. デプロイ後のURLをXに貼る

## Netlifyで公開

1. NetlifyのSitesで、このフォルダをドラッグ&ドロップする
2. 生成されたURLを開く
3. 必要ならSite settingsでURL名を変更する

## 公開前チェック

- スマホでURLを開いて、Segmentタブが動く
- 各カードをタップして詳細が開く
- `Googleマップ` ボタンで徒歩ナビが起動する
- `共有` ボタンで共有シートまたはX投稿画面が開く
- 現在地ボタンを押すと許可ダイアログが出る

## X投稿テンプレ

### 短め

HUNTER×HUNTER渋谷巡回イベント用のスマホナビを作りました。

Segment別の巡回順、キャラ確認、回収チェック、Google Maps起動まで入っています。

URL:
https://shagihagi12-art.github.io/hxh-shibuya-route/

#ハンターハンター #HUNTERHUNTER #渋谷

### 実用性訴求

渋谷のHUNTER×HUNTER巡回、Googleマイマップだとスマホで建物情報が前に出てキャラ名を追いづらかったので、現地用の軽量HTMLナビにしました。

・Segment 1〜4切替
・各スポットのキャラ表示
・回収チェック
・現在地からGoogle Maps起動

https://shagihagi12-art.github.io/hxh-shibuya-route/

#ハンターハンター #HUNTERHUNTER #渋谷

### 注意喚起込み

HUNTER×HUNTER渋谷巡回を回る人向けに、スマホ用ナビを公開しました。

撮影時は通行の邪魔にならないようにしつつ、Segment順に回れるようにしています。

https://shagihagi12-art.github.io/hxh-shibuya-route/

#ハンターハンター #HUNTERHUNTER #渋谷

## 固定ポスト向け追記

使い方:
1. URLをスマホで開く
2. Segment 1から順に回る
3. 各カードの「Googleマップ」で徒歩ナビ
4. 見つけたら「回収済みにする」

Google Mapsアプリ上のマイマップ表示に頼らず、キャラ名はHTML側で確認できます。
