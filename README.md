# pixivnovel2vec

pixiv小説で機械学習するためのスクリプト置き場

## モデルデータ配布

[Releaseページ](https://github.com/pixiv/pixivnovel2vec/releases)にて、学習済みモデルデータの配布を行っています。

## スクリプト一覧

詳細は[ブログ記事](http://inside.pixiv.net/entry/2016/09/13/161454)をご参照ください。

### doc2vec

* [学習経過](./doc2vec-train.ipynb)
	* [テストラン (サブセットデータ)](./doc2vec-train-subset.ipynb)
	* [テストラン (1回反復)](./doc2vec-train-subset.ipynb)
* [学習済みモデルの使用](./doc2vec-play-with-model.ipynb)

#### SVMによるタグ分類

* [学習経過・および結果評価](./svm-all.ipynb)
	* [テストラン (「R-18」タグ)](./svm-r18.ipynb)
	* [テストラン (「腐向け」タグ)](./svm-fumuke.ipynb)

#### K-means法による教師なし分類

* [学習経過・および結果評価](./kmeans.ipynb)

## ライセンス

本リポジトリに含まれる ipython notebook (jupyter notebook) のデータは[MITライセンス](https://opensource.org/licenses/MIT)で提供されます。
