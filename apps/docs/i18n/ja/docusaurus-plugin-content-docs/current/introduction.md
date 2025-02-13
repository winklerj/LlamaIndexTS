---
sidebar_position: 0
slug: /
---

# LlamaIndex.TSとは何ですか？

`このドキュメントは自動的に翻訳されており、誤りを含んでいる可能性があります。変更を提案するためにプルリクエストを開くことを躊躇しないでください。`

LlamaIndex.TSは、LLMアプリケーションがプライベートまたはドメイン固有のデータを取り込み、構造化し、アクセスするためのデータフレームワークです。Pythonパッケージも利用可能です（[こちら](https://docs.llamaindex.ai/en/stable/)を参照してください）、しかし、LlamaIndex.TSはTypeScriptとの使用に最適化されたシンプルなパッケージで、コア機能を提供しています。

## 🚀 LlamaIndex.TSを選ぶ理由

LLMは、人間と推論データの間の自然言語インターフェースを提供します。広く利用可能なモデルは、Wikipediaやメーリングリスト、教科書、ソースコードなど、公に利用可能な大量のデータで事前にトレーニングされています。

LLMを基に構築されたアプリケーションでは、これらのモデルにプライベートまたはドメイン固有のデータを追加する必要があります。残念ながら、そのデータはアプリケーションやデータストアに分散して存在していることがあります。APIの背後にある、SQLデータベース内にある、またはPDFやスライドデッキに閉じ込められているかもしれません。

それが**LlamaIndex.TS**の役割です。

## 🦙 LlamaIndex.TSはどのように役立ちますか？

LlamaIndex.TSは以下のツールを提供します：

- **データの読み込み**：既存の`.txt`、`.pdf`、`.csv`、`.md`、`.docx`データを直接取り込むことができます。
- **データのインデックス**：データを中間表現で構造化し、LLMが簡単かつ高速に消費できるようにします。
- **エンジン**：データへの自然言語アクセスを提供します。例えば：
  - クエリエンジンは、知識拡張出力のための強力な検索インターフェースです。
  - チャットエンジンは、データとの「やり取り」を行うための対話型インターフェースです。

## 👨‍👩‍👧‍👦 LlamaIndexは誰のためのものですか？

LlamaIndex.TSは、JavaScriptとTypeScriptを使用してLLMアプリを構築するすべての人にとって必要なツールのコアセットを提供します。

当社のハイレベルAPIを使用すると、初心者のユーザーでもLlamaIndex.TSを使用してデータを取り込み、クエリを実行することができます。

より複雑なアプリケーションでは、低レベルのAPIを使用して、データコネクタ、インデックス、リトリーバ、クエリエンジンなどのモジュールをカスタマイズおよび拡張することができます。これにより、ユーザーのニーズに合わせることができます。

## はじめに

`npm install llamaindex`

私たちのドキュメントには、[インストール手順](./installation.md)と[スターターチュートリアル](./starter.md)が含まれており、最初のアプリケーションの構築をサポートします。

一度準備ができたら、[ハイレベルなコンセプト](./concepts.md)では、LlamaIndexのモジュラーアーキテクチャの概要を説明しています。より実践的な例については、[エンドツーエンドのチュートリアル](./end_to_end.md)を参照してください。

## 🗺️ エコシステム

LlamaIndexをダウンロードしたり、貢献したりするには、以下を参照してください：

- Github: https://github.com/run-llama/LlamaIndexTS
- NPM: https://www.npmjs.com/package/llamaindex

"

## コミュニティ

ヘルプが必要ですか？機能の提案はありますか？LlamaIndexコミュニティに参加しましょう：

- Twitter: https://twitter.com/llama_index
- Discord: https://discord.gg/dGcwcsnxhU
