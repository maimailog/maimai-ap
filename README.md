# マイマイのAP単語帳

Excel・CSV・TSVをブラウザで読み込み、用語と説明を繰り返し確認する単語帳です。
単語データは同梱していません。アプリ名の「マイマイ」は公開されます。

## 保存とプライバシー

- 選択したファイルはブラウザ内で処理します。単語・学習履歴・★をサーバーへ送る処理はありません。
- データは閲覧中のブラウザのIndexedDBに保存します。ログインや端末間のクラウド同期はありません。
- ブラウザのデータを削除すると記録が失われます。データ管理からバックアップしてください。
- バックアップのJSONや単語帳のExcelには個人の内容が入ります。リポジトリへ追加しないでください。
- GitHub Pagesを開くための通信は発生します。GitHubは安全確保のため閲覧者のIPアドレスを記録します。
- 同じブラウザプロファイルを使う人や、同一オリジンで動作する別のコードからのアクセスを防ぐ認証・暗号化機能はありません。機密情報の保管用ではありません。

## GitHub Pagesへの配置

このフォルダーの index.html、JSZIP-LICENSE.md、README.md、.nojekyll、.gitignore だけを、新しい公開リポジトリに配置してください。
元の開発フォルダー、Excel、ローカル版HTML、バックアップ、過去のZIPは追加しないでください。
.gitignoreは誤追加を減らす補助で、すでにコミットされた情報を消すものではありません。

リポジトリの Settings → Pages で、公開するブランチのルートを選びます。
HTTPSを使用してください。外部CDNやAPIキーの設定は不要です。

## ローカル版から記録を移す

今使っているローカル版の「データ管理」から「学習履歴ごとバックアップ」を保存し、
公開サイトの「データ管理」からそのJSONを復元してください。ブラウザ内で処理されます。
ローカル版と公開サイトは別の保存場所です。自動移行や自動同期はしません。
URLやブラウザ、端末を変えた場合にもバックアップによる移行が必要です。

## ライセンス

Excel処理にJSZipを使用しています。配布条件はJSZIP-LICENSE.mdに記載しています。

## 参考

- https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
- https://docs.github.com/en/pages/getting-started-with-github-pages/securing-your-github-pages-site-with-https
