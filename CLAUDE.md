# Recruit Slidev Presentation

## プロジェクト概要
このレポジトリは、Slidevを使用したプレゼンテーション資料を管理するプロジェクトです。

## 現在のレポジトリ構成
- **フレームワーク**: Slidev v52.1.0
- **テーマ**: Seriph
- **メインファイル**: slides.md
- **パッケージマネージャー**: npm

## 主要ファイル
- `slides.md` - メインのプレゼンテーションファイル（Hello Worldデモ）
- `package.json` - プロジェクト設定と依存関係
- `docs/implementation-policy.md` - Claude用実装方針とガイドライン
- `.gitignore` - Gitで無視するファイルの設定
- `.npmrc` - npmの設定ファイル

## 利用可能なコマンド
- `npm run dev` - 開発サーバーを起動してプレゼンテーションをプレビュー
- `npm run build` - プレゼンテーションをビルド
- `npm run export` - プレゼンテーションをPDFなどにエクスポート

## 重要な指示
このCLAUDE.mdファイルは、レポジトリの変更に応じて常に最新の状態に保つこと。以下の項目を必ずアップデートしてください：

1. **新しいスライドの追加時**: slides.mdの構成を更新
2. **依存関係の変更時**: package.jsonの変更を反映
3. **新しいファイルの追加時**: ファイル構成の更新
4. **設定変更時**: 該当する設定項目を更新

### 実装方針の参照
詳細な実装方針とガイドラインは `docs/implementation-policy.md` を参照してください。
このファイルには以下が含まれています：
- 日本語コンテンツ作成ルール
- コミットメッセージガイドライン
- AIドリブン開発の詳細
- 自動更新プロンプトテンプレート

## 現在のスライド構成
1. タイトルスライド - "Hello World"
2. Slidevの特徴紹介
3. Thank Youスライド

## GitHub情報
- **リポジトリURL**: https://github.com/prairie-card/recruit
- **公開設定**: Public Repository

## 最終更新
- 日時: 2025-08-11
- 更新内容: Claude用実装方針ドキュメント追加、日本語ガイドライン策定