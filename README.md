# Chromeからローカルフォルダーをエクスプローラーで開くChrome拡張

## 機能
- フォルダをExplorerで開く
- （ファイルの場合）ファイルを選択した状態で親フォルダをExplorerで開く


## 対象可能なフォルダ・ファイル
- 現在のタブ（URLが `file://` 始まりの場合）
- リンク先URL（URLが `file://` 始まりの場合）
- 選択文字列（選択文字列が `C:\`, `\\ComputerName\` などで始まる場合）
    - 先頭と末尾の `"` （ダブルクォーテーション）は無視する（先頭末尾両方に存在する場合のみ）


## :warning: 注意点
Chromeからホスト側を操作するため、以下の作業が必要
- Node.jsのインストール
- レジストリの変更


## 使い方
1. 拡張をインストール
1. インストール時に開かれる `初期設定` タブに従って設定する
    - 再設定が必要な場合は、拡張のオプションページから可能
1. ページ・リンク・選択テキストの右クリックメニューから「～～をExplorerで開く」を選択
    - フォルダをExplorerで開く
    - リンク先をExplorerで開く（ローカルファイルの場合）
    - 選択文字列をExplorerで開く（ローカルファイルパスの場合）

## アイコン
[アイコン素材ダウンロードサイト「icooon-mono」](http://icooon-mono.com/) の [フォルダのアイコン素材　その2](http://icooon-mono.com/00019-%e3%83%95%e3%82%a9%e3%83%ab%e3%83%80%e3%81%ae%e3%82%a2%e3%82%a4%e3%82%b3%e3%83%b3%e7%b4%a0%e6%9d%90-%e3%81%9d%e3%81%ae2/) を使わせていただきました。
