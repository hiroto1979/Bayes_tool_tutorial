# ベイズモデリングの入門的な記録

## 目的

- Stanとjagsに入門したい
- 統一的な扱いができるか確認したい


## 方針

「ベイズ統計で実践モデリング: 認知モデルのトレーニング」(以降、教本とする)のサンプルをMarkdown化したやつを置く。

ただし、教本のjags実装はR2jagsベースのため、rjagsベースへの転記をしたうえで実装する。
可視化としてはbayesplotで行う(統一的に実施できるから、そのためにrjagsベースに転記してる)

## 内容

扱うモデルは以下の通り。

- 二項分布モデル
- 正規分布モデル
- 潜在混合モデル

トピックスは以下の通り…かな？

- Stanとjagsの入門とか、bayesplotとかの話も取り入れたい。
- Stanとjagsのパフォーマンスの差分が見たい。
  - HMCとギブスサンプリングの違いがあるはずなので  

## 参考文献

- ベイズ統計で実践モデリング: 認知モデルのトレーニング  
  [https://www.amazon.co.jp//dp/4762829978/](https://www.amazon.co.jp//dp/4762829978/)
- ベイズ統計モデリング: R,JAGS, Stanによるチュートリアル 原著第2版  
  [https://www.amazon.co.jp/dp/4320113160/](https://www.amazon.co.jp/dp/4320113160/)
- StanとRでベイズ統計モデリング (Wonderful R)  
  [https://www.amazon.co.jp/dp/4320112423/](https://www.amazon.co.jp/dp/4320112423/)
- RとStanではじめる ベイズ統計モデリングによるデータ分析入門  
  [https://www.amazon.co.jp/dp/4065165369/](https://www.amazon.co.jp/dp/4065165369/)
