課題①includerのGitStudyリポジトリを複製する。

GitBash開いて、作業ディレクトリまで移動する。

Git clone https://github.com/teamincluder/GitStudy.git

https://github.com/teamincluder/GitStudyの内容を複製（クローン）するコマンド。


②ファイルをチームリポジトリに送信する。

テキストファイルを作成する。ファイル名は"自分の名前.txt"（例：fumiya.txt）とする。

ファイルをステージングにあげる
例:git add ファイル名

--allでディレクトリ内を全部addする。
例：git add --all


ファイルをコミットする

例:git commit -a -m "めっせーじ"
-aを付けると変更ファイル全てコミット出来る
-m ""を付けるとコミットメッセージを直接入力出来る


ファイルをリモートにあげる
例：git push origin master
originはリモートの設定
masterはBranch名

