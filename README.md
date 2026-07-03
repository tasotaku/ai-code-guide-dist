# AI Code Guide（配布リポジトリ）

Python コードの理解を助ける VS Code 拡張です。フローチャート可視化・プロジェクト全体のマップ・コード内へのインライン AI 解説・AI編集検知の4つができます。

このリポジトリは**インストール用の配布ページ**です。ここから拡張機能（`.vsix`）をダウンロードして使います。

## インストール

1. **[最新リリース](../../releases/latest)** を開き、`ai-code-guide-x.y.z.vsix` をダウンロード
2. VS Code でコマンドパレット（`Cmd+Shift+P` / `Ctrl+Shift+P`）を開き、**「Extensions: Install from VSIX...」** を選択
3. ダウンロードした `.vsix` を選ぶ
4. **「Reload Window」**（ウィンドウの再読み込み）で有効化

セットアップの詳細（Python・LLM認証の準備、最初の動作確認）は **[HOWTO.md](HOWTO.md)** を読んでください。

## 更新のしかた

自動更新はされません。新しいバージョンが出たら、上と同じ手順で新しい `.vsix` を入れ直してください（バージョン番号が上がっているので上書きされます）。

各バージョンの変更点は **[CHANGELOG.md](CHANGELOG.md)** にあります。

## 必要なもの

- VS Code
- Python 3.8+（ターミナルで `python3 --version` が通ること）
- LLM の認証手段（どれか1つ）:
  - Claude のサブスク（`claude` CLI にログイン済み）— APIキー不要
  - ChatGPT Plus/Pro（`codex` CLI にログイン済み）— APIキー不要
  - Anthropic API キー

詳しくは [HOWTO.md](HOWTO.md) を参照してください。
