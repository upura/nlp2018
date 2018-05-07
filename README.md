言語処理学会第24回年次大会(NLP2018) の読んだ論文まとめ
===
# 目次
- [新聞記事における政治家の発言の引用記述と議会会議録との対応関係の調査 ―フェイクニュース検出に向けて―](https://github.com/upura/nlp2018/blob/master/README.md#%E6%96%B0%E8%81%9E%E8%A8%98%E4%BA%8B%E3%81%AB%E3%81%8A%E3%81%91%E3%82%8B%E6%94%BF%E6%B2%BB%E5%AE%B6%E3%81%AE%E7%99%BA%E8%A8%80%E3%81%AE%E5%BC%95%E7%94%A8%E8%A8%98%E8%BF%B0%E3%81%A8%E8%AD%B0%E4%BC%9A%E4%BC%9A%E8%AD%B0%E9%8C%B2%E3%81%A8%E3%81%AE%E5%AF%BE%E5%BF%9C%E9%96%A2%E4%BF%82%E3%81%AE%E8%AA%BF%E6%9F%BB-%E3%83%95%E3%82%A7%E3%82%A4%E3%82%AF%E3%83%8B%E3%83%A5%E3%83%BC%E3%82%B9%E6%A4%9C%E5%87%BA%E3%81%AB%E5%90%91%E3%81%91%E3%81%A6)
- [関連記事判定のためのニュース記事キーフレーズ抽出](https://github.com/upura/nlp2018/blob/master/README.md#%E9%96%A2%E9%80%A3%E8%A8%98%E4%BA%8B%E5%88%A4%E5%AE%9A%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AE%E3%83%8B%E3%83%A5%E3%83%BC%E3%82%B9%E8%A8%98%E4%BA%8B%E3%82%AD%E3%83%BC%E3%83%95%E3%83%AC%E3%83%BC%E3%82%BA%E6%8A%BD%E5%87%BA)
- [経済記事からの不祥事報道検知](https://github.com/upura/nlp2018/blob/master/README.md#%E7%B5%8C%E6%B8%88%E8%A8%98%E4%BA%8B%E3%81%8B%E3%82%89%E3%81%AE%E4%B8%8D%E7%A5%A5%E4%BA%8B%E5%A0%B1%E9%81%93%E6%A4%9C%E7%9F%A5)
- [決算短信からの事業セグメント情報抽出](https://github.com/upura/nlp2018/blob/master/README.md#%E6%B1%BA%E7%AE%97%E7%9F%AD%E4%BF%A1%E3%81%8B%E3%82%89%E3%81%AE%E4%BA%8B%E6%A5%AD%E3%82%BB%E3%82%B0%E3%83%A1%E3%83%B3%E3%83%88%E6%83%85%E5%A0%B1%E6%8A%BD%E5%87%BA)
- [ブートストラップ法による科学ニュース記事からの雑誌名抽出](https://github.com/upura/nlp2018/blob/master/README.md#%E3%83%96%E3%83%BC%E3%83%88%E3%82%B9%E3%83%88%E3%83%A9%E3%83%83%E3%83%97%E6%B3%95%E3%81%AB%E3%82%88%E3%82%8B%E7%A7%91%E5%AD%A6%E3%83%8B%E3%83%A5%E3%83%BC%E3%82%B9%E8%A8%98%E4%BA%8B%E3%81%8B%E3%82%89%E3%81%AE%E9%9B%91%E8%AA%8C%E5%90%8D%E6%8A%BD%E5%87%BA)
- [検索エンジンによる上位検索ページを情報源とするフェイクニュース自動検出のためのデータセット作成](https://github.com/upura/nlp2018/blob/master/README.md#%E6%A4%9C%E7%B4%A2%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%B3%E3%81%AB%E3%82%88%E3%82%8B%E4%B8%8A%E4%BD%8D%E6%A4%9C%E7%B4%A2%E3%83%9A%E3%83%BC%E3%82%B8%E3%82%92%E6%83%85%E5%A0%B1%E6%BA%90%E3%81%A8%E3%81%99%E3%82%8B%E3%83%95%E3%82%A7%E3%82%A4%E3%82%AF%E3%83%8B%E3%83%A5%E3%83%BC%E3%82%B9%E8%87%AA%E5%8B%95%E6%A4%9C%E5%87%BA%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AE%E3%83%87%E3%83%BC%E3%82%BF%E3%82%BB%E3%83%83%E3%83%88%E4%BD%9C%E6%88%90)
- [ニュースからのトピックに関するストーリーラインの生成](https://github.com/upura/nlp2018/blob/master/README.md#%E3%83%8B%E3%83%A5%E3%83%BC%E3%82%B9%E3%81%8B%E3%82%89%E3%81%AE%E3%83%88%E3%83%94%E3%83%83%E3%82%AF%E3%81%AB%E9%96%A2%E3%81%99%E3%82%8B%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AA%E3%83%BC%E3%83%A9%E3%82%A4%E3%83%B3%E3%81%AE%E7%94%9F%E6%88%90)
- [複数エンコーダを用いたヤフートピックス見出し候補生成](https://github.com/upura/nlp2018/blob/master/README.md#%E8%A4%87%E6%95%B0%E3%82%A8%E3%83%B3%E3%82%B3%E3%83%BC%E3%83%80%E3%82%92%E7%94%A8%E3%81%84%E3%81%9F%E3%83%A4%E3%83%95%E3%83%BC%E3%83%88%E3%83%94%E3%83%83%E3%82%AF%E3%82%B9%E8%A6%8B%E5%87%BA%E3%81%97%E5%80%99%E8%A3%9C%E7%94%9F%E6%88%90)
- [会話によるニュース記事伝達のための間の調整](https://github.com/upura/nlp2018/blob/master/README.md#%E4%BC%9A%E8%A9%B1%E3%81%AB%E3%82%88%E3%82%8B%E3%83%8B%E3%83%A5%E3%83%BC%E3%82%B9%E8%A8%98%E4%BA%8B%E4%BC%9D%E9%81%94%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AE%E9%96%93%E3%81%AE%E8%AA%BF%E6%95%B4)
- [プレイデータからのサッカーの速報テキスト生成](https://github.com/upura/nlp2018/blob/master/README.md#%E3%83%97%E3%83%AC%E3%82%A4%E3%83%87%E3%83%BC%E3%82%BF%E3%81%8B%E3%82%89%E3%81%AE%E3%82%B5%E3%83%83%E3%82%AB%E3%83%BC%E3%81%AE%E9%80%9F%E5%A0%B1%E3%83%86%E3%82%AD%E3%82%B9%E3%83%88%E7%94%9F%E6%88%90)
- [ファクトチェックを必要とするニュース記事の探索の支援](https://github.com/upura/nlp2018/blob/master/README.md#%E3%83%95%E3%82%A1%E3%82%AF%E3%83%88%E3%83%81%E3%82%A7%E3%83%83%E3%82%AF%E3%82%92%E5%BF%85%E8%A6%81%E3%81%A8%E3%81%99%E3%82%8B%E3%83%8B%E3%83%A5%E3%83%BC%E3%82%B9%E8%A8%98%E4%BA%8B%E3%81%AE%E6%8E%A2%E7%B4%A2%E3%81%AE%E6%94%AF%E6%8F%B4)
- [Experiment on Using Topic Sentence for Neural News Headline Generation](https://github.com/upura/nlp2018/blob/master/README.md#experiment-on-using-topic-sentence-for-neural-news-headline-generation)


# 新聞記事における政治家の発言の引用記述と議会会議録との対応関係の調査 ―フェイクニュース検出に向けて―
### 概要
フェイクニュース検出に向けた調査の研究。「新聞記事に掲載された政治家の発言の引用」と「地方議会会議録」を逐一比較していき、約95%はBoWなどの語句レベルの一致で推定できるとまとめている。

### 所感
BoWという単純な仕組みで、結構な高割合が評価できるというのは意外。ただよく考えると、新聞記事でそこまで凝った文章加工はしないので妥当な数字な気も。

# 関連記事判定のためのニュース記事キーフレーズ抽出
### 概要
ニュースサイトで良くある「関連記事」を自動で導出するタスク。「キーフレーズ共有性」という新たな評価尺度と、その概念に基づく抽出法を提案している。

### 所感
計算量の節約のためにRNNによる近似を導入したら、性能も上がったという報告が興味深い（本論文の考察でも理由は十分に掘り下げられていない）。


# 経済記事からの不祥事報道検知
### 概要
経済記事を「不祥事」に関するものか否かで二値分類するシステムの開発。アルゴリズムはロジスティクス回帰とN-gram。精度を追い求めるだけでなく、解釈性・頑健性などを深く議論している。

### 所感
機械学習を実システムに導入する際のTipsのような論文。

# 決算短信からの事業セグメント情報抽出
### 概要
決算短信特有の言語的な特徴を考慮した「事業セグメント情報抽出手法」を提案し、その有用性について実データを用いて評価。

### 所感
ドメイン知識をフル活用して、実直にタスクに取り組んでいる。

# ブートストラップ法による科学ニュース記事からの雑誌名抽出
### 概要
雑誌名が特定の文脈に出現しやすいという仮定を立て、雑誌名の両側から学習した文脈をパターンとして利用しブートストラップ法で雑誌名を抽出

### 所感
論文の第一文のこの問題の解消が根本的な解決策ではないかと思ったり。。。

> 日本語の科学ニュース記事では，研究成果がわかりやすく述べられるが，出典となる文献情報は明記されない傾向にある．

# 検索エンジンによる上位検索ページを情報源とするフェイクニュース自動検出のためのデータセット作成
### 概要
フェイクニュース検出に関して、人間と同じやり方（検索エンジンによる上位検索ページを情報源として判断）をコンピュータで再現しようとした論文。

### 所感
うまくいかなかった例を分析した結果「検索された結果ページにフェイクニュースの記事のほうが多く存在してしまう場合」が挙げられていて、そうだよなあと思った。このアプローチだとどうやっても人間を大きく超える性能は出せないだろうが、目的は「データセット作成」に置いているので悪くもない気もする。

# ニュースからのトピックに関するストーリーラインの生成
### 概要
ニュースコーパスからトピック (知りたい事柄) に関連するテーマを抽出し，そのテーマに関連する文が時系列順に並んだ文集合 (ストーリーライン) を出力するシステムを提案。

### 所感
「ストーリーラインの生成」というタスクを、細かいタスクに分解している。他の研究成果を動員して実現する応用研究のような立ち位置。

# 複数エンコーダを用いたヤフートピックス見出し候補生成
### 概要
「記事タイトル」と「記事リード文」を入力とし、エンコーダ・デコーダの枠組みからトピックス見出しを生成する手法を提案。

### 所感
単に先行研究をサービスに適用するだけでなく、技術的な修正もしているのが良い。

# 会話によるニュース記事伝達のための間の調整
### 概要
会話によるニュース記事伝達において、割り込みを許容しながら快適なリズムで会話を進行させるための間の調整について検討。テクノロジー系のニュース記事 100 個を人手で要約・口語化し、実際に声優に話してもらいコーパスを作成。双方向 LSTMやBayesianRidgeモデルで学習させた。

### 所感
スマートスピーカーが流行っている中、ある意味新しいジャーナリズムの形を模索する論文と言っても良い気がする。

# プレイデータからのサッカーの速報テキスト生成
### 概要
「選手名やチーム名を汎化タグに変換」「単語bigramを1つの単語として結合」の工夫で、encoder-decoder[6]モデルの性能が向上。  
https://www.nikkei.com/article/DGXMZO29812440V20C18A4X90000/

### 所感
直感的にも性能改善しそうな前処理をすることで、実際に性能が改善しており、腑に落ちやすかった。

# ファクトチェックを必要とするニュース記事の探索の支援
### 概要
ファクトチェックの必要性を示唆する情報（＝「端緒情報」）の探索を自動化し，人手による要検証記事探索作業を技術的に支援する仕組みを構築。

### 所感
うまくいかなかった例を見ていると、人間の発言をコンピュータに解釈させることの難しさを改めて実感する。

# Experiment on Using Topic Sentence for Neural News Headline Generation
### 概要
encoder-decoderモデルを用いたニュースの見出し生成タスクで、第一文ではなく「トピックセンテンス」を使った場合の影響を調べる。第一文に加えてトピックセンテンスも利用した方が性能が上がった。

### 所感
多様な情報を利用した方が精度は出そうなので、最後はどこかで計算コストと性能のトレード・オフみたいな話に帰着しそう。
