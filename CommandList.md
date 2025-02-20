# よく使うGitコマンドとオプション

## 基本的なコマンド
- `git init` - 新しいGitリポジトリを作成
- `git clone <repository>` - リモートリポジトリをローカルにクローン
- `git status` - 現在のリポジトリの状態を表示
- `git add <file>` - ファイルをステージングエリアに追加
- `git add .` - すべての変更をステージングエリアに追加
- `git commit -m "<message>"` - ステージングエリアの変更をコミット
- `git push` - ローカルのコミットをリモートリポジトリにプッシュ
- `git pull` - リモートリポジトリから変更を取得してマージ

## ブランチ操作
- `git branch` - ブランチの一覧を表示
- `git branch <branch>` - 新しいブランチを作成
- `git switch <branch>` - 指定したブランチに切り替え
- `git merge <branch>` - 指定したブランチを現在のブランチにマージ
- `git branch -d <branch>` - ブランチを削除

## リモートリポジトリ
- `git remote -v` - リモートリポジトリのURLを表示
- `git remote add <name> <url>` - 新しいリモートリポジトリを追加
- `git fetch` - リモートリポジトリから変更を取得
- `git push <remote> <branch>` - 指定したリモートリポジトリにブランチをプッシュ
- `git pull <remote> <branch>` - 指定したリモートリポジトリからブランチをプル

## その他の便利なコマンド
- `git log` - コミット履歴を表示
- `git diff` - 変更点を表示
- `git stash` - 作業中の変更を一時的に保存
- `git stash pop` - 一時的に保存した変更を適用
- `git reset --hard` - すべての変更を取り消してリポジトリを最新のコミットにリセット
- `git rebase <branch>` - 指定したブランチの変更を現在のブランチに適用
