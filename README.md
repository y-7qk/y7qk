# 左右反転画像 生成プログラム flip.py
## 1.概要
引数で指定した画像の左右反転画像を作成するpython3で動作するプログラムです。
## 2.ソースコード
~~~python
# このプログラムは python3用です。
# あらかじめ pip install pillow で pillow をインストールしておきます。
from PIL import Image
import sys

# コマンドライン引数から入力画像と出力画像のファイル名を取得
input_image = sys.argv[1]
output_image = sys.argv[2]

# 画像の読み込み
img = Image.open(input
~~~
