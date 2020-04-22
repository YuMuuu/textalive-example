# github pagesに最速で公開するためのテンプレート

## 初期設定
- yarn install

- pre-commit(commit時に自動でbuild出来るように設定する)
``` 
sh pre-commit-setting.sh
```

- gh-pages branchを作る 
```
git checkout -b gh-pages
```

## メモ
github pagesにはroutingがない（？）のでカレントディレクトリにhtml,js,css出力するようにしています。また/src以下のファイルに変更が無い場合でも現状毎回commit時にbuildが走るようになっています
