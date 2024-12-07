# 「PyTorch自然言語処理プログラミング」の学習に用いたリポジトリです．
> 新納浩幸；PyTorch自然言語処理プログラミング，2021，インプレス．

## コードの概要
[pytorch_learn_01.ipynb](pytorch_learn_01.ipynb)は１章（pytorchの基本的な使い方，iris判別タスク）<br>
２章（word2vec）はほぼ同じ内容をゼロつく２でやっていた上，ライブラリを使うだけの章だったのでパス<br>
[pytorch_learn_02.ipynb](pytorch_learn_02.ipynb)は３章（LSTMによる自然言語処理の学習，品詞分解タスク）<br>
[pytorch_learn_03.ipynb](pytorch_learn_03.ipynb)は４章（Seq2seqによる本格的な自然言語処理，NMT，機械翻訳タスク）<br>
５章（BERTによる自然言語処理，タスクに合わせたモデル調整）は一旦パス
> １度目の学習時はハッカソン期間で，開発しているものとは遠かったのでパス
---

## フォルダの概要
```datasets,pkls,models```は.gitignoreで追跡対象から外していますが，
- ```datasets```は，東北大学による日本語wikipediaから学習した日本語分散表現のエンティティベクトル
- ```pkls```には，書籍内で学習に用いられている日本語文章の単語とベクトル，対応する品詞のリスト
- ```models```には，学習したモデル
- ```enja_datasets```には，４章で用いた和文英文，単語のデータセット

を保存していました

> ```datasets``` from https://www.cl.ecei.tohoku.ac.jp/~m-suzuki/jawiki_vector/<br>
> ```pkls``` from https://book.impress.co.jp/books/1119101184<br>
> ```enja_datasets`` from https://github.com/odashi/small_parallel_enja


