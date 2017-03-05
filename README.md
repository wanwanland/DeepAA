README.md

# DeepAA
## 概要
ディープラーニング技術を用いて画像をアスキーアートに変換します。

## 前提
動作にはPythonの実行環境が必要です。

以下の環境でテスト済みです。

+ Python 3.5 (64bit)

## 依存パッケージ
本ライブラリは以下のパッケージに依存しています。

+ TensorFlow
+ Keras
+ NumPy
+ Pillow (PIL Fork)

## 使用方法
`deepaa_output.py ` の17行目

```
image_path = 'test_image.png' # 変換する画像を指定
```
の画像パスを任意のものに置き換えて実行してください。
画像は白黒の線画を用いてください。
細線化された画像の方が良い結果が得られやすいです。

現段階では学習済みモデルによる出力を行うコードのみ公開しています。
学習データの前処理、学習のコードは今後公開の予定です。

## 実行例
![出漁サンプル.png](C:\Users\oakiyama\Pictures\出漁サンプル.png)
## ライセンス
本ライブラリのライセンスは `MIT License` になります。