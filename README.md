# kaggle-titanic

## 概要
kaggleチュートリアルの[titanic](https://www.kaggle.com/c/titanic)のデータセットを用いた分類問題

## データセット
データセットの説明は[こちら](https://www.kaggle.com/c/titanic/data)をご参照ください。

## 環境
R言語（version.string R version 3.4.1 (2017-06-30)）

## アルゴリズム
1. ロジスティック回帰
2. ランダムフォレスト

## 作業手順


- 訓練データとテストデータの読み込み
- 欠損値の補完
- 変数の作成



- ロジスティック回帰の場合

  4. ロジスティック回帰分析の実行
  5. vif（多重共線性）の確認
  6. ステップワイズ法にて変数の選択
  7. テストデータへモデルを当てはめ予測を行う

- ランダムフォレストの場合

  4. ランダムフォレストの実行
  5. 特徴量の数と木の個数を調整
  6. テストデータへモデルを当てはめ予測を行う
  
