# Office-Addin-Projectへようこそ！
詳細な情報は[Github wiki](https://github.com/hakumai22/Office-Addin-Project/wiki)に書かれています。
セットアップ、デプロイ方法、用語解説なども載っています。
## ブランチについて
主な開発ブランチはdevelopにする予定です。 
コンフリクトを防ぐためにdevelopブランチには直接コミットしないことを推奨します。
main→developへのマージは安定的に動作するかつ完成度が高くなってきた場合、以下の条件を満たした場合マージされます。
* 厳密なコードレビューが行われている
* 本番環境でのバグチェックが行われているかつ安定的に動作する
* 同意を得ている  

以下の場合は直接mainにコミットしても大丈夫です。逆にdevelopには出さないでほしいです。（プルリクを出してくれたら１日のうちには対応します）
* Readme.md

ブランチ構成を図に示すと、
<pre>
main
└── develop
    └── some branches(bug_fix,ui_design,code_prepare,update_futureなど)
</pre>
という感じです。


### コンフリクト対策について
まだ詳細には決まっていませんが、
* mainで変更するもの
* developで変更するもの
* developでのプルリクで変更するもの

の三つに分ける予定です。
