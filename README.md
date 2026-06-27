# DANMAKU - ブラウザ弾幕シューティング

依存なしのHTML5 Canvasゲームです。`index.html` をブラウザで開くだけで遊べます。

## 起動

```bash
cd ~/git/shooting-game
python3 -m http.server 8080
```

ブラウザで以下を開きます。

```text
http://localhost:8080/
```

## 操作

- 移動: 矢印キー / WASD
- ショット: Z / Space
- 低速移動: Shift
- ポーズ: P

自機の中心の小さな点だけが当たり判定です。Shiftを押すと当たり判定が見えます。

## 内容

- 通常ウェーブ
- 4種類の敵弾パターン
- 5ウェーブごとのボス
- ボスの3段階弾幕
- スコア、ライフ、ハイスコア保存
- 被弾時の弾消しと無敵時間
