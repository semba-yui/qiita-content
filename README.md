# qiita-content

Qiita 記事管理用 リポジトリ

# 主なコマンド集

## Preview

```Shell
npx qiita preview
```

## 同期

```Shell
npx qiita pull
```

## 投稿

```Shell
npx qiita publish
```

## 参考

```Shell
$ npx qiita help   
USAGE:
qiita <COMMAND> [<OPTIONS>]

COMMAND:
  init                    記事をGitHubで管理するための初期設定
  login                   Qiita APIの認証認可
  new [<basename>] ...    新しい記事を追加
  preview                 コンテンツをブラウザでプレビュー
  publish <basename> ...  記事を投稿、更新
  publish --all           全ての記事を投稿、更新
  pull                    記事ファイルをQiitaと同期
  version                 Qiita CLIのバージョンを表示
  help                    ヘルプを表示

OPTIONS:
  --credential <credential_dir>
    Qiita CLIの認証情報を配置するディレクトリを指定

  --root <root_dir>
    記事ファイルをダウンロードするディレクトリを指定

  --verbose
    詳細表示オプションを有効

  --config
    設定ファイルを配置するディレクトリを指定

詳細についてはReadme(https://github.com/increments/qiita-cli)をご覧ください
```
