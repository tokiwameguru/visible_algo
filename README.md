# Visible Algo
ダイクストラ法（最短経路を求めるアルゴリズム）や二分探索木の構築などを、実際に選択したデータファイルから読み取って構築＆画像で出力するGUIアプリケーションです。

## 開発の経緯
アルゴリズムを実際に実装して動かしてみることはそれまでも時々やっていたのですが、入出力がCUIで完結していたので物足りなさや不便さを感じていました。そこでGUIで操作できるようにしてもっと扱いやすくしよう！という思いから作成したものがVisible Algoになります。

## 使用技術
- Python
- tkinter (PythonのGUIライブラリ)
- Graphviz (グラフ描画ライブラリ)

## ホーム画面
それぞれボタンをクリックするとファイルのダイアログが開き、読み込むデータファイルを選択できます。
![20220227032739](https://user-images.githubusercontent.com/48623999/162594498-f2fa18fc-b554-4aae-9f71-3c6efe38f664.png)


## ダイクストラ法の実行結果例
![20220227032901](https://user-images.githubusercontent.com/48623999/162594502-402a899f-3bcb-45f2-93b1-c46e95c2eb63.png)

#### 操作画面上にも文字として結果が出力されます。
![20220227032932](https://user-images.githubusercontent.com/48623999/162594544-3e268170-4626-4758-b93d-4c51b2d19392.png)
