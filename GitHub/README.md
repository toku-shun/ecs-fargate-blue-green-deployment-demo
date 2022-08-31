# Nginx Demo コンテナ

## 概要

index.htmlをトップページとするnginxを作成するコンテナ。
ECSへのBlue/Greenデプロイ用の下記ファイルも格納。自身の環境に応じて値を変更すること。

- appspec.yaml
- system-dev-taskdef.json

## コマンド

```[shell]

# ビルド
$ docker build -t <イメージ名>:<タグ名> .

```
