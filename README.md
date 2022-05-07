# push_test
ディレクトリを作成する

```
$ mkdir (ディレクトリ名)
```

作成したらそこに移動する

```
$ cd (ディレクトリ名)
```

gitの初期設定

```
$ git init
```

push先を設定する

```
$ git remote add origin git@github.com:hideki1224/push_test.git
```

ファイルを追加、編集

gitにpushする準備

```
$ git add (ファイル名)  
$ git commit -m "メッセージ"
$ git push -u origin main
```

ファイルの状態確認に使用
```
$ git status
```