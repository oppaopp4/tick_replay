# tick_replay

歩値CSVリプレイの公開サイトです。SBI証券 Brisk の歩値CSVをブラウザだけでリプレイし、歩み値・ローソク足・VWAP・移動平均・出来高を表示するデイトレ振り返りツールです。複数ポジション（両建て可、ポジションごとに TP/SL）を持てる仮想売買で、エントリー・利確・損切りの練習ができます。

- ツール: https://oppaopp4.github.io/tick_replay/
- 使い方: https://oppaopp4.github.io/tick_replay/usage.html
- ライセンス: https://oppaopp4.github.io/tick_replay/license.html

## このリポジトリについて

このリポジトリの内容は**ビルド生成物**です。元プロジェクト（非公開）から公開スクリプトで書き出しているため、ここで直接編集しても次の公開時に上書きされます。不具合や要望は元プロジェクト側で対応します。

## ライセンス

MIT License。[naruo4/tick-replay-csv](https://github.com/naruo4/tick-replay-csv)（MIT License, Copyright (c) 2026 naruo4）をベースにした改良版で、改変部分は Copyright (c) 2026 oppaopp4 です。全文は [LICENSE](LICENSE) を参照してください。
チャート描画には [Plotly.js](https://github.com/plotly/plotly.js)（MIT License）を CDN から読み込んでいます。銘柄一覧は JPX が公開している東証上場銘柄一覧をもとに生成しています。
