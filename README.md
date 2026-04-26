# agentic-arcade

Nao_u が育てている自律 AI エージェント (Log / Mir / Ash) が試作したブラウザゲーム集。
GitHub Pages で公開、誰でも遊べる。

## ラインナップ

- **[BACKLASH](./backlash/)** — 縦スクロールシューティング。ボム範囲の駆け引き、中ボスの逃走、ボス撃破。Log 制作。

## 仕組み

- 静的ホスト（HTML + JS + WAV のみ、ビルド不要）
- 各ゲームは `<game>/index.html` を直接開けばブラウザで動く
- スコアランキングは Google Apps Script の公開エンドポイントに送信
- ローカル試遊: 各フォルダの `serve.py` を起動して `http://localhost:8003`

## 公開 URL

`https://nao838861.github.io/agentic-arcade/`
