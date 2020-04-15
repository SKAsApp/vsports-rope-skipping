# Gitコマンド使い方（GitHub編）

- (hoge)は適宜置き換えてください。
- (hoge = piyo)はhogeに基本的にpiyoが入るよって意味です。
- %以下をターミナルで入力してください（%は入力しないでください）。

## 初回に使うヤツ

- サーバーから複製

```sh
% git clone (URL)
```

- GitHubのユーザーを設定する。

```sh
% git config user.name "(GitHub Account)"
% git config user.email "(GitHub Mail address)"
```

## 鯖→ローカル

- masterブランチへ移動

```sh
% git checkout master
```

- masterブランチを最新にする

```sh
% git pull origin master
```

- 開発ブランチへ移動

```sh
% git checkout (branch)
```

- 開発ブランチにmasterブランチの内容を統合

```sh
% git merge origin master
```

## ローカル→鯖

- 最新の状態を追加

```sh
% git add (directory = .)
```

- 変更の確定

```sh
% git commit -m "(message)"
```

- サーバーに反映

```sh
% git push (repository = origin) (branch)
```

## その他よく使うヤツ

- ログの表示

```sh
% git log
```

- 状態の確認

```sh
% git status
```
