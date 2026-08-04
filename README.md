# ローカルLLM実践研修 Day1 ハンズオン⓪

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/goto-yuta/local-llm-handson/blob/main/day1-colab.ipynb)

Google Colab の無料GPU(T4)で、Ollama を使って Qwen3 の 0.6B / 4B / 8B を動かすハンズオン用ノートブックです。
研修受講者への配布のみを目的としています。

- 手順書:https://local-llm-training-2026.web.app/day1/handson-colab
- 上のバッジ、または[このリンク](https://colab.research.google.com/github/goto-yuta/local-llm-handson/blob/main/day1-colab.ipynb)から Colab で直接開けます
- 開いたら「ランタイム」→「ランタイムのタイプを変更」→ **T4 GPU** にしてから、上のセルから順に実行してください

## 測定値の共有について

ノートブックには、測った速さ(tok/s)と到達段階を教室の集計ボードへ送る処理が入っています。

- 設定セルの `SHARE = False` にすると、一切送信しません
- 送るのは速さ・到達段階・GPU種別・席番号だけです。**プロンプトやモデルの出力は送りません**
- `BOARD_KEY` は集計先を指すための Firebase のウェブ用公開識別子で、モデルの推論には一切関係しません

© Kikagaku, Inc.
