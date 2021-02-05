# ML_LSTM

## 使い方（Train）

1. "Clone"を選択し、"Download ZIP"を押してダウンロードする。

![1](./readme-images/1.png)

2. ダウンロードしたzipファイルを解凍し、GoogleドライブのROOTディレクトリに解凍したディレクトリをおく。

ROOTディレクトリに置く理由は、プログラム上でそのように定義してあるから。その箇所を書き換えれば、その他のディレクトリでも問題ない。

![2](./readme-images/2.png)

3. 「lstm_train.ipynb」を右クリックして、「アプリを開く」＞「Google Colaboratory」を選択する。

![3](./readme-images/3.png)

4. 「Runtime」タブの「Change Runtime Type」を選択する。

![4](./readme-images/4.png)

5. GPUを選択し、保存する。

![5](./readme-images/5.png)

6. 「Connect」を選択する。

![6](./readme-images/6.png)

7. 「Runtime」タブの「Run all」を選択する。

![7](./readme-images/7.png)

8. 図のように、実行される。初めて実行するとき、Googleドライブへのアクセスを聞かれるが、URLを選択し、アカウントを選択する。その後、表示されるKEYをコピーし、Colabの入力欄に入力する。

![8](./readme-images/8.png)

9. 実行終了後、学習済みのモデルがGoogleドライブにコピーされているのを確認する。

![9](./readme-images/9.png)

## 使い方（Predict）

trainと同様に実行すると、result_predict.csvがそれぞれのディレクトリに保存される。

## メモ

- 学習するデータはdatasetの中にある。
- 学習するモデルはLSTM_1とLSTM_2のふたつを準備している。これはプログラムを修正して追加・削除が可能。
