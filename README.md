# ChitChat

* config.json で設定を変更することができます
* chitchat.log ファイルにログが書き出されます
* テストファイルがあります
* 構造体がすべて細かく定義されています（本文中では明確には記述されていませんでした）
* 一部の関数は（パッケージの一部ではなく）構造体のメソッドになっています

## 実行の手順

1. ＜Postgresを起動＞
2. createdb chitchat
3. psql -f data/setup.sql -d chitchat
4. go build
5. ./chitchat
