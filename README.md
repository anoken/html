# HTML Mini Apps Collection

ブラウザで動くミニアプリ・ゲーム・シミュレーションのコレクションです。
すべて単一HTMLファイルで完結し、外部ライブラリ不要で動作します。

## デモ一覧

| アプリ名 | 説明 | リンク |
|---------|------|--------|
| 男をさがせ！ | 女性の中に隠れた男性を探す間違い探しゲーム（レベル制・タイム計測） | [Play](https://anoken.github.io/html/otoko_sagase.html) |
| プリけつを探せ！ | ハートの中に隠れたプリけつを探す間違い探しゲーム（15レベル・記録保存） | [Play](https://anoken.github.io/html/oshiri_sagase.html) |
| Oを探せ！視力検査ゲーム | CとOの画像から正解のOを探す視力検査風ゲーム | [Play](https://anoken.github.io/html/shiryoku_game.html) |
| 振動絶縁シミュレーション | スマホの加速度センサーを使った振動絶縁のリアルタイムシミュレーション | [Play](https://anoken.github.io/html/vibration_isolation.html) |
| リアルタイム スペクトログラム | マイク入力からリアルタイムでスペクトログラムを表示する音声可視化ツール | [Play](https://anoken.github.io/html/spectrogram.html) |
| Digital Rain | マトリックス風のデジタルレインエフェクト（カタカナ・英数字） | [Play](https://anoken.github.io/html/digital-rain.html) |
| スロットゲーム | 絵柄を揃えるカジノ風スロットゲーム（2バージョン） | [v1](https://anoken.github.io/html/slot.html) / [v2](https://anoken.github.io/html/slot_2.html) |
| 台車型倒立振子バランスゲーム | 加速度センサー/キーボードで台車を操作し、振子を立て続けるゲーム（RK4物理演算） | [Play](https://anoken.github.io/html/inverted_pendulum.html) |
| 倒立振子 振り上げ制御 | 下向きの振子を揺さぶって逆立ちさせ、バランスをキープするシミュレーション | [Play](https://anoken.github.io/html/inverted_pendulum_swingup.html) |
| 麻雀ドラフト | ターン制ドラフト型の麻雀役構築ゲーム（4人対戦・役判定付き） | [Play](https://anoken.github.io/html/mahjong_draft.html) |
| コップの水シミュレーション | 加速度センサーでコップの中の水の動きをシミュレーション | [Play](https://anoken.github.io/html/water_cup_drift.html) |
| 花粉ビューワー | 住所を入力して花粉の飛散状況をビジュアル表示 | [Play](https://anoken.github.io/html/pollen_view.html) |
| モールス信号変換器 | カタカナを和文モールス信号に変換し、音と光で再生・WAV保存が可能 | [Play](https://anoken.github.io/html/morse_code.html) |

## ディレクトリ構成

```
html/
├── README.md
├── LICENSE
├── docs/                          # GitHub Pages 公開ディレクトリ
│   ├── digital-rain.html          # Digital Rain
│   ├── inverted_pendulum.html     # 倒立振子バランスゲーム
│   ├── inverted_pendulum_swingup.html # 倒立振子 振り上げ制御
│   ├── mahjong_draft.html         # 麻雀ドラフト
│   ├── morse_code.html            # モールス信号変換器
│   ├── oshiri_sagase.html         # プリけつを探せ
│   ├── otoko_sagase.html          # 男をさがせ
│   ├── pollen_view.html           # 花粉ビューワー
│   ├── shiryoku_game.html         # 視力検査ゲーム
│   ├── slot.html                  # スロットゲーム v1
│   ├── slot_2.html                # スロットゲーム v2
│   ├── spectrogram.html           # スペクトログラム
│   ├── vibration_isolation.html   # 振動絶縁シミュレーション
│   ├── water_cup_drift.html       # コップの水シミュレーション
│   ├── image_oshiri/              # プリけつ探し用画像
│   ├── image_otoko_sagase/        # 男探し用画像
│   └── image_shiryoku/            # 視力検査ゲーム用画像
└── public/
    └── readme.md
```

## 動作環境

- モダンブラウザ（Chrome, Safari, Firefox, Edge）
- 一部アプリはスマートフォンの加速度センサーを利用（HTTPS環境が必要）
- 一部アプリはマイクへのアクセスが必要
