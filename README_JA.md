<p align="center">
 <picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/atuinsh/atuin/assets/53315310/13216a1d-1ac0-4c99-b0eb-d88290fe0efd">
  <img alt="Atuin Desktop" src="https://github.com/atuinsh/atuin/assets/53315310/08bc86d4-a781-4aaa-8d7e-478ae6bcd129">
</picture>
</p>

<h1 align="center">Atuin Desktop</h1>

<p align="center">
  <em>実行可能なRunbook。実際のターミナルワークフローに対応した、ローカルファーストで実行可能なRunbookエディター。Atuin Desktopはドキュメントのように見えますが、ターミナルのように動作します。</em>
</p>


<p align="center">
  <a href="https://github.com/atuinsh/desktop/releases">download</a> | <a href="https://man.atuin.sh">documentation</a> | <a href="https://hub.atuin.sh/">hub</a> | <a href="https://discord.gg/Fq8bJSKPHh">discord</a>
</p>


<p align="center">
 <picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://man.atuin.sh/images/atuin-desktop-ss-dark.png">
  <img alt="Atuin Desktop" src="https://man.atuin.sh/images/atuin-desktop-ss-light.png">
</picture>
</p>

（[English](README.md), [日本語](README-ja.md)）

## 🚀 オープン ベータ

Atuin Desktopは**オープン ベータ中**です。皆様からのフィードバックを積極的に収集し、実際の使用状況に基づいてエクスペリエンスを改善しています。

[アナウンス ポスト](https://blog.atuin.sh/atuin-desktop-open-source/)を読む。

## Atuin Desktopとは何ですか?

ほとんどのインフラは、何か問題が起きたときに誰かが思い出す5つのコマンドで支えられています。ドキュメントは古く（そもそも存在するかどうかさえも）、真の答えはSlackのスレッドに埋もれたり、Notionで散らかったり、誰かのシェル履歴に閉じ込められたりしています。

Atuin Desktopは、ドキュメントと自動化のギャップを埋める実行可能なRunbookを作成することでこの問題を解決します:

- **コンテキストスイッチをなくす**: シェルコマンド、データベースクエリ、HTTPリクエストを1か所にまとめる
- **ドキュメント腐らせない**: 直接実行して関連性を保つ
- **再利用可能な自動化**: Jinjaスタイルのテンプレートを使用した動的なRunbook
- **瞬時のリコール**: 実際のシェル履歴からのオートコンプリート
- **ローカルファースト、CRDT駆動**: ターミナルで実行できるものはRunbookでも実行できる
- **同期と共有**: Atuin Hubを使用してデバイスやチーム間でRunbookを最新の状態に保つ

## 主な特徴

### 🔧 組み込み実行
- インターフェース内で直接実行されるターミナルブロック
- ライブクエリ用のデータベースクライアント
- Prometheusチャートと監視統合

### 📚 生きたドキュメント
- 実行可能なRunbook
- 古いドキュメントからのコピーペーストは不要
- チームが実際に使用できるワークフロー

### 🔄 動的テンプレーティング
- 再利用可能なロジックのためのJinjaスタイルのテンプレーティング
- 変数の置換と条件付きロジック
- 異なる環境のためのパラメータ化されたワークフロー

### 🏛 ローカルファーストアーキテクチャ
- CRDT駆動のコラボレーション
- オフラインで動作し、接続時に同期

## ユースケース

既に導入しているチームはAtuin Desktopを以下の目的で使用しています:

- **リリース管理**: 実際に実行される自動化されたリリースチェックリスト
- **インフラストラクチャの移行**: 安全で再現性のある移行ワークフロー
- **環境管理**: 自信を持ってステージングとプロダクションを立ち上げる
- **データベース操作**: コラボレーティブなライブクエリ管理
- **インシデント対応**: 障害発生時のRunbook

## はじめましょう

1. ご利用のプラットフォームにあわせたパッケージを [リリースページ](https://github.com/atuinsh/desktop/releases)からダウンロード
2. [Atuin Hub](https://hub.atuin.sh/)でアカウントにサインアップ
3. Atuin Desktopに[ログイン](https://man.atuin.sh/hub/getting-started/)し、最初のRunbookを作成

## フィードバックとサポート

私たちはベータ版の期間中にフィードバックを積極的に求めています！このリポジトリを使用して、以下のことを行ってください。

### 🐛 問題の報告
- バグを見つけましたか？ [問題を開く](../../issues/new?template=bug_report.md)
- OS、Atuin Desktopのバージョン、再現手順を含めてください

### 💡 機能リクエスト
- アイデアがありますか？ [機能リクエストを提出](../../issues/new?template=feature_request.md)
- ワークフローについて教えてください。Atuin Desktopがどのようにサポートできるかを教えてください

### 💬 一般的な議論

使用に関する質問がありますか？ [ディスカッションを開始](https://forum.atuin.sh)

## ロードマップ

### 今後の予定
- **強化された統合**: より多くのデータベースクライアント、監視ツール、API
- **履歴からRunbookへ**: シェル履歴から自動的にRunbookを生成

## コミュニティ

- **Blog**: [blog.atuin.sh](https://blog.atuin.sh)
- **Discord**: [コミュニティに参加](https://discord.gg/Fq8bJSKPHh)
- **Twitter**: [@atuinsh](https://twitter.com/atuinsh)
- **Bluesky**: [@atuin.sh](https://bsky.app/profile/atuin.sh)
- **Website**: [atuin.sh](https://atuin.sh)

## 関連するプロジェクト

- **[Atuin CLI](https://github.com/atuinsh/atuin)**: 同期、検索、統計機能を備えた魔法のシェル履歴

## License

Copyright 2025 Atuin, Inc

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
