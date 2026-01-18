# 修士課程の研究

## 概要
このリポジトリは、修士論文「レーザー散乱砲を用いたりんご果実の力学的特性および粉質化の推定」で使用したソースコードとデータをまとめています。
- 各章の分析コード、データ処理、結果出力が章ごとに整理されています。

### 環境構築
- `pyproject.toml`に依存関係が記載されているので、uvを使用してPython環境を構築してください（Python 3.13.5以上推奨）。
- `.gitignore`: Git管理から除外するファイルの設定。

> [!Note]
> Chapter4, 5_2, 5_3の`data`と`output`は容量が大きいので、必要な人は連絡してください。

## ディレクトリの説明
```
- master
    - Chapter3
        - code
        - data
        - output
    - Chapter4
        - code
        - data
        - output
    - Chapter5_2
        - code
        - data
        - output
    - Chapter5_3
        - code
        - data
        - output
    - README.md
    - pyproject.toml
    - uv.lock
    - .gitignore
```