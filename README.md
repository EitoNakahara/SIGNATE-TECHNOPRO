# SIGNATE-TECHNOPRO
最終評価26位の解法になります。

#### モデル
*   Transformerベースのモデルのスコアが良かったため、Vit TransformerとSwin Transformerのアンサンブルを採用。
*   CNNベースのResNet, EfficientNetはベースラインほど出なかった。

#### 実施しなかったこと
*   前処理
*   ハイパーパラメータのチューニング
*   後処理

#### コンペで学んだこと
*   モデルによって、得意不得意があるため、とにかくたくさんのモデルで試してみることが大切。今回試さなかったEva02でスコアが伸びたようだ。
*   上位解法に画像をグループ分けするというものがあった。学習データがデータ拡張で作成されていたため、似たような画像の扱い方を意識することが大切だったようだ。次の画像コンペではもっと画像に特徴がないか念入りに調べたい。
