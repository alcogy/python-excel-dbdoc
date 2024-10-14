# excel-to-ddl

テーブル定義書からDDLを作成するためのツールです。

### 準備
ライブラリをインストールします。
```
pip install openpyxl
```

### 使い方

1. テンプレート用のエクセルファイル (DatabaseSpec.xlsx)でテーブル仕様書を作成します。
2. ddl.pyを実行します。
```
python ./ddl.py
```
