README：TortoiseGitのインストール(リモートデスクトップ側)

「以下を参照」
http://moondoldo.com/DoldoWorkz/index.php?Git%2FWindows%E3%81%A7%E4%BD%BF%E3%81%86%28msysgit%E3%83%BBTortoiseGit%29

１．DownloadZIPを押してダウンロード、解凍

２．Git-2.6.4-32-bit.exeを実行してインストール

３．TortoiseGit-1.8.16.0-32bit.msiを実行してインストール

４．TortoiseGit-LanguagePack-1.8.16.0-32bit-ja.msiをインストール（日本語に対応しないなら不要）

５．プロキシの設定	Windowsの適当なところで右クリック：TortoiseGit：設定：ネットワークで

	サーバーアドレス	127.0.0.1

	ポート				8080

	ユーザ名			Uxxxxxx(自ID)

	パスワード			xxxxxxx(自Password)


※開発ノートPCではGitHub.exeを実行しインストール（手順は秋谷さんメールを参照）


基本動作：

・TortoiseGitではクローンやリポジトリのウインドウで右クリック

	Git同期：最新化

	Gitコミット：更新ファイルのアップロード


・GitHubではアプリを起動後

	Historyボタン、Syncボタン：最新化

	Changesボタン：ファイルを選択後、Commit：更新ファイルのアップロード

