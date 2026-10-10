# Coffee Dripper Designer

Mac・Windows用アプリのダウンロードと自動更新用の配布場所です。

[最新版をダウンロード](https://github.com/zoo904/coffee-dripper-designer-releases/releases/latest)

- **Mac（Apple Silicon）**: `arm64.zip`を展開し、アプリをApplicationsへ移してください。
- **Windows（64 bit）**: `windows-x64.zip`を展開し、中のSetupを実行してください。ZIP内のREADMEも確認してください。

Beta 10以降は起動時に更新を確認します。更新がない場合はホームに「最新の状態です」と表示します。編集中に更新が届いた場合は、保存してから更新ボタンで適用できます。更新の取得にはインターネット接続が必要です。GitHubのアカウントやTailscaleは必要ありません。

Mac版はDeveloper ID署名・Apple公証済みです。Windowsの初回Setupには現時点でAuthenticode署名がないため、OSの発行元警告が出る可能性があります。以後のWindows自動更新では署名された更新情報と本体のハッシュを検証します。SHA-256一覧は各Releaseの`SHA256SUMS.txt`にあります。

このrepositoryは配布専用です。アプリのソースコード、利用者の作品、アカウント情報、秘密鍵は掲載しません。GitHubが表示する「Source code」の自動生成アーカイブには、この配布案内のみが含まれます。
