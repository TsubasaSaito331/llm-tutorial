# LLM 入門

## **リポジトリ構成**

### train.ipynb

簡単な Q&A を行う LLM を学習させています。

### config.yaml

train.ipynb のモデルや生成時の設定が書いてあります。

このファイルの設定を変えるだけでモデルを

## **おすすめ書籍**

### [大規模言語モデル入門](https://amzn.asia/d/1AkMkfI)

LLM の基礎を学べます。実装の前に基礎を固めたいという場合はこちら。

- Transformer
- GPT
- 固有表現抽出
- LLM のユースケース
  - 要約
  - 質疑応答
  - 文章分類

### [大規模言語モデル入門 Ⅱ〜生成型 LLM の実装と評価](https://amzn.asia/d/6lourQu)

LLM の実装&評価を学べます。

- 日本語 LLM
- ファインチューニング
  - LoRA
  - 指示チューニング
  - 思考チューニング
- RAG
- 生成文の評価（llm-as-a-judge）
- など

## **おすすめの Web サイト**

### **基礎の勉強に役立つ Web サイト**

### [大規模言語モデル](https://speakerdeck.com/chokkan/llm)

言語モデルや Transfomer の基礎や機械学習などの情報が紹介されています。

「言語モデル」「Transformer」とは何ぞや？という人向け

### [大規模言語モデルの開発](https://speakerdeck.com/chokkan/jsai2024-tutorial-llm)

LLM の開発におけるステップを紹介しています。

「継続事前学習」「指示チューニング」「RLHF」とは何ぞや？という人向け

### [GPT とは何か Transformer の視覚化 | Chapter 5, Deep Learning](https://youtu.be/KlZ-QmPteqM?si=nanwYvI-LBhTPtEt)

### [GPT 解説 2 アテンションの仕組み (Attention, Transformer) | Chapter6, 深層学習](https://youtu.be/j3_VgCt18fA?si=dSlo4QOEQcotv4Mh)

youtube の動画で GPT 内部での挙動が視覚的に表現されており、大規模言語モデルや Transformer の動作が直感的に理解できます。

### [LLM を効率的に再学習する手法(PEFT)を解説](https://www.brainpad.co.jp/doors/contents/01_tech_2023-05-22-153000/)

LoRA とフルファインチューニングとの違いがよくわからない人向けの記事です。

PEFT の種別を紹介してくれています。

![](/api/attachments.redirect?id=fc0a240a-799c-451f-8175-d51004a5b614)

### **実装に役立つ Web サイト**

### [Huggingface - models](https://huggingface.co/models?pipeline_tag=text-generation&sort=trending)

LLM を使うのであれば必須になるサイトです。

最新のモデルやデータセットが随時更新されており、ページ内でデモが行えるモデルもあります。

推論をさせるだけならモデルページのコードをコピペするだけでローカルで LLM を使用することができます。

### [東大松尾・岩澤研究室 | LLM 開発 プロジェクト\[GENIAC\]](https://zenn.dev/p/matsuolab)

松尾研が開発している LLM の技術的な記事が載っています。

学習時のデータについてや MoE 学習の効果などが紹介されています。
