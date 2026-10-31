# HTML Mini Apps Collection

ブラウザで動くミニアプリ・ゲーム・シミュレーションのコレクションです。
ほとんどは単一HTMLファイルで完結し、外部ライブラリ不要で動作します（クイズ4本は画像フォルダ付き）。

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
| 重心テトリス | 重心を意識して積む物理テトリス | [Play](https://anoken.github.io/html/gravity-tetris.html) |
| からあげレモン戦争 | 相手が振り向かない隙にからあげへレモンを搾る3Dアクションゲーム（Three.js、ベストスコア保存） | [Play](https://anoken.github.io/html/karaage-lemon.html) |
| 総理大臣クイズ | 歴代総理大臣66人の顔写真から名前を当てる3択クイズ（10問・毎回出題が変わり難易度が上がる） | [Play](https://anoken.github.io/html/prime-minister-quiz/) |
| 歴代天皇クイズ | 初代神武天皇から今上天皇まで52人の肖像とヒントから名前を当てる3択クイズ | [Play](https://anoken.github.io/html/emperor-quiz/) |
| 歴代お札クイズ | 明治以降のお札の肖像になった21人を当てる3択クイズ（人物当て・券種当ての2形式） | [Play](https://anoken.github.io/html/banknote-quiz/) |
| アメリカ歴代大統領クイズ | 歴代大統領45人の公式肖像から名前を当てる3択クイズ | [Play](https://anoken.github.io/html/us-president-quiz/) |

## ディレクトリ構成

```
html/
├── README.md
├── LICENSE
├── docs/                          # GitHub Pages 公開ディレクトリ
│   ├── digital-rain.html          # Digital Rain
│   ├── gravity-tetris.html        # 重心テトリス
│   ├── karaage-lemon.html         # からあげレモン戦争
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
│   ├── image_shiryoku/            # 視力検査ゲーム用画像
│   ├── prime-minister-quiz/       # 総理大臣クイズ（index.html + img/）
│   ├── emperor-quiz/              # 歴代天皇クイズ（index.html + img/ + images.json）
│   ├── banknote-quiz/             # 歴代お札クイズ（index.html + img/ + images.json）
│   └── us-president-quiz/         # アメリカ歴代大統領クイズ（index.html + img/ + images.json）
└── public/
    └── readme.md
```

## クイズの画像について

- 総理大臣クイズの顔写真は[首相官邸ホームページ「歴代内閣」](https://www.kantei.go.jp/jp/rekidainaikaku/index.html)のもので、政府標準利用規約（第2.0版、CC BY 4.0 互換）に基づき出典を明記して利用しています。
- 天皇・お札・大統領クイズの肖像は Wikimedia Commons のパブリックドメインまたは CC0 の画像です。各ページ下部の「画像の出典一覧」と `images.json` にファイル名・作者・ライセンスを記載しています。
- お札クイズは紙幣の券面画像を使わず、肖像になった人物の写真・肖像画のみを使用しています。

## 動作環境

- モダンブラウザ（Chrome, Safari, Firefox, Edge）
- 一部アプリはスマートフォンの加速度センサーを利用（HTTPS環境が必要）
- 一部アプリはマイクへのアクセスが必要
- からあげレモン戦争は Three.js（r128）を CDN から読み込むため、ネット接続が必要
