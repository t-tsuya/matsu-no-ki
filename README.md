# My Project: Multi-Model Machine Learning Framework

このプロジェクトは、PyTorch を用いて複数のモデル（例：Simple Autoencoder、その他のモデル）を実装・学習するためのフレームワークです。

## ディレクトリ構成

- **data/**: データセットや前処理スクリプトを管理します。
- **notebooks/**: Colab や Jupyter Notebook 形式のファイル（探索的実験用）。
- **src/**: 本番用コード
  - **models/**: 各種モデルの定義（例：autoencoder.py, other_model.py）。
  - **train.py**: 学習ループ、モデル選択を含む実行スクリプト。
  - **evaluate.py**: 評価・推論用スクリプト。
  - **utils.py**: 補助的な関数群（プロットなど）。
- **tests/**: ユニットテスト。
- **requirements.txt**: 依存パッケージ一覧。
- **.gitignore**: Git管理から除外するファイル。

## セットアップ

以下のコマンドで依存パッケージをインストールしてください。

```bash
pip install -r requirements.txt
