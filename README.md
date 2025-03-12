
# Tourism Data Analysis

## 概要
このリポジトリは、観光庁が提供する「インバウンド消費動向調査」のデータを用いて、訪日外国人の消費動向を分析するためのものです。このデータを通じて、観光業界への洞察を深め、データドリブンな意思決定をサポートすることを目的としています。

## ディレクトリ構成
```
root/
├─ data/
│  ├─ input/
│  ├─ inter/
│  └─ output/
├─ notebooks/
├─ references/
├─ setting/
├─ pyproject.toml
└─ poetry.lock
```

### ディレクトリの詳細
- **data/**: このディレクトリは、入力データ（input）、加工後の中間データ（inter）、出力データ（output）を格納します。
- **notebooks/**: 分析に使用するノートブックファイルを格納します。
- **references/**: カラム名のリストや特定のカラムのコード値を変換するためのリストなど、参照用のドキュメントを格納します。
- **setting/**: ファイルのパス、パラメータ設定などの設定ファイルを格納します。

## 出典
- **データの取得先**: [インバウンド消費動向調査 個票データリクエストフォーム](https://forms.office.com/pages/responsepage.aspx?id=tHnszZFsA028z7Rz1aWXolpufOwFT_NOkbGF3eYuKLVUMFFHTEtIMFU5SEZZQzMyR1pQNlhWQ09CVyQlQCN0PWcu&origin=lprLink&route=shorturl)
- **参照先**: [国土交通省 観光庁 インバウンド消費動向調査（旧 訪日外国人消費動向調査）](https://www.mlit.go.jp/kankocho/tokei_hakusyo/gaikokujinshohidoko.html)
