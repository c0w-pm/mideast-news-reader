# mideast-news-reader

# Mideast News Reader

中東6媒体のニュースをAIが要約・音声読み上げするWebアプリ。

## 対応メディア

- アルジャジーラ
- イランインターナショナル
- アルモニタ
- エルサレム・ポスト
- ミドルイーストモニター
- タイムズオブイスラエル

## 現在の機能

- 記事URLを入力するとClaude APIで要約・分析
- 口語体に変換して音声読み上げ（文間ポーズあり）
- インパクトスコア自動判定（HIGH/MID/LOW）
- キーワードボタンで優先度カスタマイズ
- 単位自動換算（ガロン→リットル、マイル→kmなど）
- AI質問欄（原文ベースと背景知識を明示分離）
- Claude/ChatGPTへのプロンプト一括コピー

## 開発ログ

- 2026/05/15 フロントエンド完成・GitHub Pages公開

## 今後の予定

- GitHub Actionsで記事自動取得（RSS監視）
- 新着通知
- 媒体追加・削除機能

## 技術スタック

- HTML/CSS/JavaScript（静的サイト）
- Claude API（Haiku）
- Web Speech API
- GitHub Pages / GitHub Actions
