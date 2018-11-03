# ci-build-project

## プロジェクト概要

- 既存サービスを活用したCI環境の構築
- ソースをリポジトリにpush -> build -> deploy -> notification の自動化
- 可能な限り無料枠で構築する

## 利用サービス（予定）

- GitHub
- Travis CI
- Heroku
- Slack

## 参考記事

## メモ

- [x] GitHubアカウントを作る
- [x] GitHubにリポジトリをpushする
- [x] Travis CIの設定する
  - GitHubアカウントでTravis CIにログイン
  - リポジトリ選んでactivateボタンを押す
  - ビルド設定ファイル `.travis.yml` をリポジトリに作成する
  - 対象言語、ビルドオプションを設定（この辺り手間がかかる）
- [ ] Slackに通知用のChannelを作成
- [ ] Slack上でTravis CI setupする
