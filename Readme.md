# Office-Addin-Projectへようこそ！
詳細な情報は[Github wiki](https://github.com/hakumai22/Office-Addin-Project/wiki)に書かれています。
## ブランチについて
主な開発ブランチはdevelopにする予定です。 
コンフリクトを防ぐためにdevelopブランチには直接コミットしないことを推奨します。
main→developへのマージは安定的に動作するかつ完成度が高くなってきた場合、以下の条件を満たした場合マージされます。
* 厳密なコードレビューが行われている
* 本番環境でのバグチェックが行われているかつ安定的に動作する
* 同意を得ている  


ブランチ構成を図に示すと、
<pre>
main
└── develop
    └── some branches(bug_fix,ui_design,code_prepare,update_futureなど)
</pre>
という感じです。
