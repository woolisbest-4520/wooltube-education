### WOOLtube Education

WOOLtube Education は、**YouTube Education（youtubeeducation）専用プレーヤー**を利用して動画を再生する Web アプリです。動画の検索には **YouTube Data API（公式 API）** を使用し、ユーザーが利用したい API を自由に選択できるようになっています。

---

## 📌 特徴

- **YouTube Education 埋め込み専用**のシンプルな動画再生ツール
- **YouTube 公式 API を利用した動画検索**が可能
- API キーは **自動取得（またはユーザー設定）** に対応
- API 使用回数は **1 日 100 回** のため、使えない場合は別の API を選択可能
- Education 用のパラメーター・キーはシステム側で自動取得

---

## 🛠 使用しているAPI

- **YouTube Data API v3（検索）**
- **YouTube Education 埋め込み API（再生）**

ユーザー側で、利用したい API を自由に選択できます。

---

## 🚀 使い方

### 1. 動画を検索

- 検索ボックスにキーワードを入力し、YouTube Data API を使って検索します。
- 取得された動画 ID が一覧表示されます。

### 2. 動画 ID・動画URL

- 自動取得された API キーも使用されます。

### 3. youtubeeducation 形式で再生

- 動画 ID とパラメーターを元に、Education 埋め込みプレーヤーで再生します。

---

## 📂 ディレクトリ構成（例）

project-root/
├── LICENSE
├── index.html
└── README.md


---


## ⚙ 設定

### API キーについて

- 1 日 100 回まで利用可能。
- 上限を超えたり動作しない場合は他の API キーへ切り替えてください。
- youtubeeducation 用の key・パラメーターはシステムが自動で取得します。

---


### パラメーター取得元について
WOOLtube Education は以下 3 箇所からパラメーターを自動取得します：

- [パラメーター1](https://raw.githubusercontent.com/woolisbest-4520/about-youtube/refs/heads/main/parameter.json)
- [パラメーター2](https://raw.githubusercontent.com/woolisbest-4520/about-youtube/refs/heads/main/edu.json)
- [幸せokさん](https://raw.githubusercontent.com/siawaseok3/wakame/master/video_config.json)

これらのいずれかは必ず利用可能なため、もし使用不可のパラメーターがあった場合は別のパラメーターセットを選択してください。

---


## 📝 注意事項

- YouTube Data API の制限により、検索回数には上限があります。
- YouTube Education 埋め込みが使用不可の場合、通常の埋め込みとは挙動が異なる場合があります。
- 動画が教育カテゴリに属さない場合、表示されない可能性があります。

---


## 📄 ライセンス

[GPL-3.0 license](https://github.com/woolisbest-4520/wooltube-education?tab=GPL-3.0-1-ov-file)

---


## 🤝 貢献

バグ報告・改善案など歓迎しています。
