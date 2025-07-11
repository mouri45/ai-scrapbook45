# Andrej Karpathy: Software Is Changing

https://www.youtube.com/watch?v=LCEmiRjPEtQ&ab_channel=YCombinator

元 Tesla AI ディレクターである Andrej Karpathy 氏が、Y Combinator の AI Startup School で語った「AI 時代のソフトウェア」についての講演内容を以下にまとめます。

### AI 時代のソフトウェア開発：3 つのパラダイム

Karpathy 氏は、ソフトウェア開発の歴史を 3 つの時代に分けて説明しました。

1.  **Software 1.0 (〜2012 年): 手動コーディングの時代**
    人間が Python や C++などのプログラミング言語を使って、コンピュータに実行させたい命令を一行一行記述する伝統的な方法。

2.  **Software 2.0 (〜2022 年): ニューラルネットワークの時代**
    人間が直接コードを書くのではなく、大量のデータ（例：画像とラベル）を用意し、ニューラルネットワークを訓練します。このとき、プログラムの実体はネットワークの「重み（weights）」となります。Tesla の自動運転で、画像認識部分が従来の C++コードを置き換えていったのがこの例です。

3.  **Software 3.0 (現在〜): LLM（大規模言語モデル）の時代**
    プログラムは、英語などの自然言語で書かれた「プロンプト」によって作られます。LLM は、もはや単なるツールではなく、**新しい種類の OS（オペレーティングシステム）**と考えるべきだと Karpathy 氏は提唱します。

    - **CPU**: LLM 自体
    - **RAM**: コンテキストウィンドウ
    - **周辺機器**: ブラウザ、計算機、ファイルシステムなどのツール

### LLM の特性：「認知的な問題を抱えたサヴァン」

LLM は人間に関する膨大なテキストで学習しているため、独特の「心理」を持っています。これを理解することが、LLM をうまく活用する鍵となります。

- **超人的な能力**: 百科事典のような知識と驚異的な記憶力を持つ（映画『レインマン』のよう）。
- **認知的な欠陥**:
  - **ハルシネーション**: もっともらしい嘘をつく。
  - **Jagged Intelligence (ギザギザの知性)**: 難しいことはできるが、簡単な計算や常識的な判断を間違う。
  - **前向性健忘**: コンテキストウィンドウの外のことは忘れてしまう（映画『メメント』のよう）。継続的な学習が苦手。
  - **騙されやすさ**: プロンプトインジェクションに弱い。

### スタートアップにとっての大きな機会

この新しいパラダイムは、スタートアップにとって計り知れない機会を生み出します。

#### 1. アイアンマンスーツを作る（部分的自律性アプリ）

完全自律のエージェント（アイアンマンロボット）を目指すのではなく、人間を強力に補佐する「アイアンマンスーツ」のような製品に大きな可能性があります。

- **人間と AI の協調ループ**: AI が「生成」し、人間が「検証」するワークフローを構築し、そのループをいかに高速化するかが重要です。
- **優れた UI/UX**: 人間が AI の生成物を素早く、直感的に検証・修正できるインターフェースが成功の鍵となります。
- **自律性スライダー**: ユーザーがタスクの複雑さに応じて、AI の自律性の度合いを調整できる機能が有効です（例：Cursor, Perplexity）。

#### 2. エージェントのために世界を再構築する

これまでのデジタルインフラはすべて人間向けに作られてきました。今後は、LLM エージェントという**新しい種類のユーザー**のために、これらを再設計する必要があります。

- **LLM 向けのドキュメント**: 人間向けのドキュメントだけでなく、LLM が理解しやすい Markdown 形式の`llms.txt`のようなファイルを用意する（Vercel や Stripe が既に導入）。
- **LLM フレンドリーな API**: 「クリック」のような人間向けの指示ではなく、LLM が直接実行できるコマンド（cURL など）を用意する。

#### 3. Vibe Coding（バイブス・コーディング）の普及

専門家でなくても、自然言語で「こんな感じ（vibe）で」と伝えるだけでソフトウェアが作れるようになります。これにより、ソフトウェア開発は爆発的に民主化され、子供でもアプリを作れる時代が到来します。

### 結論

ソフトウェア開発は、人間が直接コードを書く時代から、人間が AI と対話し、その働きを監督する時代へと根本的に変化しています。この過渡期において、人間と AI の協調を円滑にするツールや、AI エージェントが活動しやすいインフラを構築することに、スタートアップにとっての莫大なチャンスが眠っています。
