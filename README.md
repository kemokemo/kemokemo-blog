# kemokemo-blog

## Start

```sh
git clone https://github.com/kemokemo/kemokemo-blog.git --recursive
```

```sh
hugo server
```

## Add contents

「せや、今日の日付で書こう」と思ったら、以下のコマンドで新しいポスト用のMarkdownファイルを作れる。

```sh
hugo new posts/$(date +%Y-%m-%d).md
```

上記コマンドで新規ファイルを作る際`archetypes/default.md`が使われるので、なにか初期設定を追加したいならそれを編集する。

## Memo

長いURLなんかを直接Markdownに記述すると、めっちゃ横長の画面になってしまってスマホ表示で横の表示が切れるので注意。
