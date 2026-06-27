# DANMAKU - ブラウザ弾幕シューティング

HTML5 Canvasだけで動く、ブラウザ用の弾幕シューティングです。

Play:
https://jyoshise.github.io/shooting-game/

Repository:
https://github.com/jyoshise/shooting-game

## 起動

```bash
cd ~/git/shooting-game
python3 -m http.server 8765
```

ブラウザで開きます。

```text
http://127.0.0.1:8765/
```

## 操作

PC:

- 移動: 矢印キー / WASD
- ショット: Z / Space
- 低速移動: Shift
- ボム: X
- ポーズ: P
- ミュート: M

スマホ:

- 画面ドラッグ: 移動
- ドラッグ中: 自動ショット
- ダブルタップ: ボム

## 主な機能

- EASY / NORMAL 難易度選択
- 以前より弾速・敵速を遅めに調整
- 8種類の敵タイプ
  - 直進ザコ
  - 3-way狙い撃ち
  - リング弾
  - 扇状弾
  - 横切り編隊
  - 分裂弾
  - 予告線つきスナイパー
  - 低速ホーミング弾
- 複数の編隊パターン
- 5ウェーブごとのボス
- ボスの3段階弾幕
- パワーアップアイテム
- ボム
- グレイズ（弾かすり）
- コンボ倍率
- WebAudioによる効果音
- ライフ/ボム/パワー/HUD表示
- ハイスコア保存
- スマホ対応
- タブ非表示時の自動ポーズ
- シードRNGによる再現しやすいランダム

## ルール

自機の中心の白い点だけが当たり判定です。
Shiftを押すとグレイズ範囲が見えます。
弾をかすめるとGRAZEが増え、スコア倍率維持に役立ちます。

## License

MIT
