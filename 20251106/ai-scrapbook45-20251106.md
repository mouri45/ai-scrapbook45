# このページについて

- 2025/10/03 から 2025/11/06 の期間で、個人的に気になった AI ニュース/記事/ポストなどまとめたページです。
- TechFirst Leaders の社内 AI 勉強会用に整理したものを公開しています。
- Web 開発/システム開発エンジニア寄りの視点でまとめています。
- まとめた人：[@mouri45](https://x.com/mouri45)

# 気になるトピック

- OpenAI が AI ブラウザの ChatGPT Atlas をリリース。(今のところ開いてるページの要約くらいしか使い道がないかも)
- OpenAI DevDay 2025 で、ChatGPT 内で外部アプリを呼び出せる App SDK、AI Agent ワークフローの AgentKit,Agent Builder などが公開。
- Anthropic が Claude Code が Web 上で動作する Claude Code on web がリリース。その他 Claude Skills、Claude Code Plugin などをリリース。
- Cursor 2.0 リリース。独自モデルの Composer、エージェントを並行で動作させるマルチエージェント、内部ブラウザの高機能化など

# カテゴリ

**AI 企業/LLM 関連ニュース**：[OpenAI](#openai) | [Google](#google) | [Anthropic](#anthropic) | [MS/GitHub](#msgithub) | [Amazon](#amazon) | [ローカル LLM](#ローカル-llm) | [その他 LLM 関連](#その他-llm-関連)

**注目トピック**：[AI コーディング/AI 駆動開発](#ai-コーディングai-駆動開発) | [MCP](#mcp) | [AI エージェント](#ai-エージェント) | [ローカル LLM](#ローカル-llm) | [ロボティクス](#ロボティクス)

**ツール/サービス**：[開発/情報系](#気になるツールサービス-1開発情報系) | [画像/動画/3D 等](#気になるツールサービス-2画像動画3d音声音楽生成認識技術xrゲーム関連等) | [その他](#その他)

# AI 企業/LLM 関連ニュース

## OpenAI

### [OpenAI DevDay 2025 発表まとめ](https://zenn.dev/schroneko/articles/openai-devday-2025)

![OpenAI DevDay 2025 発表まとめ](https://res.cloudinary.com/zenn/image/upload/s--i_BdwPX9--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:OpenAI%2520DevDay%25202025%2520%25E7%2599%25BA%25E8%25A1%25A8%25E3%2581%25BE%25E3%2581%25A8%25E3%2582%2581%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%25AC%25E3%2581%2593%25E3%2581%25AC%25E3%2581%2593%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzE4ZDE4NWExYTYuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [ChatGPT 内でアプリを直接操作する Apps SDK に自作のアプリを接続する](https://azukiazusa.dev/blog/chatgpt-apps-sdk/)

![ChatGPT 内でアプリを直接操作する Apps SDK に自作のアプリを接続する](https://azukiazusa.dev/blog/ogp/chatgpt-apps-sdk.png)

Apps in ChatGPT は ChatGPT のチャット内で会話の流れに応じて外部のアプリを呼び出し、インタラクティブな操作を可能にする機能です。アプリごとに独自の UI コンポーネントを提供し、ユーザーはチャット画面からシームレスな体験でアプリを操作できます。この記事では Apps SDK を使用して、実際に ChatGPT 内で動作するシンプルなアプリを作成する手順を紹介します。

---

### [OpenAI AgentKit の概要と使い方【Agent Builder / ChatKit / Connector Registry】](https://zenn.dev/galirage/articles/openai-agentkit)

![OpenAI AgentKitの概要と使い方【Agent Builder / ChatKit / Connector Registry】](https://res.cloudinary.com/zenn/image/upload/s--hq9jEe4y--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:OpenAI%2520AgentKit%25E3%2581%25AE%25E6%25A6%2582%25E8%25A6%2581%25E3%2581%25A8%25E4%25BD%25BF%25E3%2581%2584%25E6%2596%25B9%25E3%2580%2590Agent%2520Builder%2520%252F%2520ChatKit%2520%252F%2520Connecto...%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:%25E3%2581%25BE%25E3%2581%2599%25E3%2581%25BF%2520%252F%2520%25E7%2594%259F%25E6%2588%2590AI%25E3%2582%25A8%25E3%2583%25B3%25E3%2582%25B8%25E3%2583%258B%25E3%2582%25A2%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2ExNzA3YjIxM2QuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/g_south_west%2Ch_34%2Cl_default:og-publication-pro-mark-xcosax%2Cw_34%2Cx_217%2Cy_158/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:Galirage%2520Inc.%2Cx_255%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2M5ZDA3ZmI1ZGEuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [エージェント構築実践ガイド.pdf](https://cdn.openai.com/pdf/37dce0c6-b190-4cf6-b6b9-2651fe6af98a/%E3%82%A8%E3%83%BC%E3%82%B7%E3%82%99%E3%82%A7%E3%83%B3%E3%83%88%E6%A7%8B%E7%AF%89%E5%AE%9F%E8%B7%B5%E3%82%AB%E3%82%99%E3%82%A4%E3%83%88%E3%82%99.pdf)

---

### [ChatGPT 搭載のブラウザー、ChatGPT Atlas が登場](https://openai.com/ja-JP/index/introducing-chatgpt-atlas/)

![ChatGPT 搭載のブラウザー、ChatGPT Atlas が登場](https://images.ctfassets.net/kftzwdyauwt9/7C3BcyFP7a5ND61x2LaS0Q/96c45b882ff992f9deca082f51c0585f/Atlas_Blog_OpenGraph_Image.png?w=1600&h=900&fit=fill)

Web 上のどこでも ChatGPT を利用できます。

---

### [AI ブラウザ｢ChatGPT Atlas｣に脆弱性発覚。専門家が注意を喚起](https://www.gizmodo.jp/2025/11/vulnerability-discovered-in-chatgpt-atlas.html)

![AIブラウザ｢ChatGPT Atlas｣に脆弱性発覚。専門家が注意を喚起](https://media.loom-app.com/gizmodo/dist/images/2025/11/04/shutterstock_2693164977.jpg?w=1280&h=630&f=jpg)

アドレスバーに悪意のコマンドが勝手に入力されるんだって。Google Chrome に対抗して、OpenAI がリリースした AI ブラウザ｢ChatGPT Atlas｣（現在 Mac 版のみ）に、さっそくセキュリティの穴が見つかり、セキュリティ需要の高い情報を取り扱わないよう専門家たちが警鐘を鳴らしています。個人情報覚えすぎ Atlas ブラウザでは、｢Memories｣という Web 使用履歴保存機能を組み入れ

---

### [X ユーザーの ITmedia AI ＋さん: 「OpenAI、ChatGPT に Slack や Google ドライブに分散する情報を横断検索する「company knowledge」追加 https://t.co/PHCrDuY57W」 / X](https://x.com/itm_aiplus/status/1982570448677400633)

![XユーザーのITmedia AI＋さん: 「OpenAI、ChatGPTにSlackやGoogleドライブに分散する情報を横断検索する「company knowledge」追加 https://t.co/PHCrDuY57W」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

## Google

### [Google AI Studio、ビルドモードで AI アプリを Vibe Coding するための新しい UX を提供 | gihyo.jp](https://gihyo.jp/article/2025/10/vibe-coding-ai-app-using-google-ai-studio-build-mode)

![Google AI Studio、ビルドモードでAIアプリをVibe Codingするための新しいUXを提供 | gihyo.jp](https://gihyo.jp/assets/images/ICON/2025/2671_vibe-coding-ai-app-using-google-ai-studio-build-mode.png)

Google は 2025 年 10 月 21 日、Google AI Studio において、Vibe Coding で AI アプリを作成するための新しいユーザーエクスペリエンスを提供開始した。

---

### [X ユーザーの ChatGPT 研究所さん: 「【速報】Google が最新動画生成 AI Veo 3.1 および Veo 3.1 Fast を発表！ ・音声の表現力が向上 ・映像精度アップ ・参照動画を元に生成 ・開始、終了フレームを指定可能に ・動画延長機能 API, Flow, Gemini アプリ,Vertex AI から使用可能。既に使えました！ https://t.co/3yB4XAiyxZ」 / X](https://x.com/ctgptlb/status/1978516786174644251)

![XユーザーのChatGPT研究所さん: 「【速報】Googleが最新動画生成AI Veo 3.1およびVeo 3.1 Fastを発表！   ・音声の表現力が向上 ・映像精度アップ ・参照動画を元に生成 ・開始、終了フレームを指定可能に ・動画延長機能  API, Flow, Geminiアプリ,Vertex AIから使用可能。既に使えました！ https://t.co/3yB4XAiyxZ」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [Gemini 2.5 Computer Use の概要｜ npaka](https://note.com/npaka/n/n3104d25dae88)

![Gemini 2.5 Computer Use の概要｜npaka](https://assets.st-note.com/production/uploads/images/220749522/rectangle_large_type_2_6c5e9e19e9ac6d848689b752f592a024.png?fit=bounds&quality=85&width=1280)

以下の記事が面白かったので、簡単にまとめました。 ・Introducing the Gemini 2.5 Computer Use model 1. Gemini 2.5 Computer Use 「Gemini 2.5 Computer use」は、「Gemini 2.5 Pro」の視覚理解・Reasoning 機能を基盤として構築された、UI を操作できるエージェントを実現する新しい専用モデルです。このモデルは、複数の Web およびモバイル制御ベンチマークにおいて、主要な代替モデルを凌駕し、しかも低レイテンシを実現しています。 2. 仕組み このモデルのコア機能は、「Ge

---

### [Google、誰でも学べる AI 学習サイト「Google Skills」を正式公開 ──Cloud・DeepMind・教育部門を横断する 3000 講座を展開 | Ledge.ai](https://ledge.ai/articles/google_skills_ai_learning_platform_launch)

![Google、誰でも学べるAI学習サイト「Google Skills」を正式公開──Cloud・DeepMind・教育部門を横断する3000講座を展開 | Ledge.ai](https://storage.googleapis.com/ledge-ai-prd-public-bucket/media/Keyword_blog_header_2096x1182_width_1200_format_webp_539cc78549/Keyword_blog_header_2096x1182_width_1200_format_webp_539cc78549.webp)

AI・人工知能関連のニュースやトレンドを高頻度で配信！最新ニュースやインタビュー、イベントレポートなど AI に関するさまざまな情報を独自の切り口で掲載

---

## Anthropic

### [Web 上で Claude Code を実行できる「Claude Code on the web」リサーチプレビュー版で提供開始 | gihyo.jp](https://gihyo.jp/article/2025/10/claude-code-on-the-web)

![Web上でClaude Codeを実行できる「Claude Code on the web」リサーチプレビュー版で提供開始 | gihyo.jp](https://gihyo.jp/assets/images/article/2025/10/claude-code-on-the-web/001.png)

Anthropic は 2025 年 10 月 21 日、AI コーディングエージェント Claude Code を Web から操作できる「Claude Code on the web」をリサーチプレビュー版としてリリースした。

---

### [Anthropic、Claude のカスタマイズ機能「Skills for Claude」リリース](https://www.itmedia.co.jp/aiplus/articles/2510/17/news060.html)

![Anthropic、Claudeのカスタマイズ機能「Skills for Claude」リリース](https://image.itmedia.co.jp/aiplus/articles/2510/17/cover_news060.jpg)

Anthropic は、Claude を特定タスクの専門家に変えるという新機能「Skills for Claude」をリリースした。指示やコードをまとめた「Skills」を自動で読み込み、Excel 操作や独自ガイドラインの順守など、専門的な作業の精度を高める。API 経由でも利用可能だ。

---

### [X ユーザーの Kinopee さん: 「Anthropic の Skills リポジトリ。サンプルファイルが多数公開されています。 https://t.co/hwgTxqhHGJ」 / X](https://x.com/kinopee_ai/status/1978861091296780732)

![XユーザーのKinopeeさん: 「Anthropic の Skills リポジトリ。サンプルファイルが多数公開されています。 https://t.co/hwgTxqhHGJ」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [X ユーザーのぬこぬこ | NUKO さん: 「Claude Haiku 4.5 が公開 Sonnet 4 と比べてコーディングで同等性能、コストは 3 分の 1、速度は 2 倍以上。特定のタスクでは Sonnet 4 を超える。API では claude-haiku-4-5。価格は 100 万トークンあたり入力 $1、出力 $5。最も安全なモデル。Bedrock と Vertex AI でも。 https://t.co/WRvkkgI9QO」 / X](https://x.com/schroneko/status/1978549989002608640)

![Xユーザーのぬこぬこ | NUKOさん: 「Claude Haiku 4.5 が公開  Sonnet 4 と比べてコーディングで同等性能、コストは 3 分の 1、速度は 2 倍以上。特定のタスクでは Sonnet 4 を超える。API では claude-haiku-4-5。価格は 100 万トークンあたり入力 $1、出力 $5。最も安全なモデル。Bedrock と Vertex AI でも。 https://t.co/WRvkkgI9QO」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [X ユーザーの Oikon さん: 「【Claude Code の新機能 Plugin システム】 Claude Code 拡張機能として、以下を配布できるようになった ・Slash commands ・Agents (Subagents) ・MCP サーバー ・Hooks `/plugin` コマンドで実行可能。 基本的な流れ: 1. Marketplace に Plugin を追加 2. Plugin を Install 3. Plugin を利用 https://t.co/Lo7aVbfsaV」 / X](https://x.com/oikon48/status/1976456500714635691)

![XユーザーのOikonさん: 「【Claude Code の新機能 Pluginシステム】  Claude Code拡張機能として、以下を配布できるようになった  ・Slash commands ・Agents (Subagents) ・MCPサーバー ・Hooks   `/plugin` コマンドで実行可能。  基本的な流れ:  1. Marketplace に Pluginを追加 2. PluginをInstall 3. Pluginを利用 https://t.co/Lo7aVbfsaV」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [AI エージェントのための効果的なコンテキストエンジニアリング｜ sutoh](https://note.com/lab_bit__sutoh/n/n7796b223fe13)

![AIエージェントのための効果的なコンテキストエンジニアリング｜sutoh](https://assets.st-note.com/production/uploads/images/219453991/rectangle_large_type_2_efba7e98976a671c9e4fd328241a74c8.png?fit=bounds&quality=85&width=1280)

Anthropic からコンテキストエンジニアリングの良い記事が出ましたので、翻訳にしました。

Effective context engineering for AI agents

Anthropic is an AI safety and research company that's working

www.anthropic.com

要旨 LLM 活用の重心がプロンプト作成から「コンテキストエンジニアリング」へ移行していることを示し、Transformer 由来の注意予算やコンテキストロットによる性能劣化を前提に、高シグナル最小トークン集合を設計・維

---

## MS/GitHub

### [マイクロソフト、MCP や A2A プロトコルに対応した AI エージェント開発を容易にする「Microsoft Agent Framewok」プレビュー公開](https://www.publickey1.jp/blog/25/mcpa2aaimicrosoft_agent_framewok.html)

![マイクロソフト、MCPやA2Aプロトコルに対応したAIエージェント開発を容易にする「Microsoft Agent Framewok」プレビュー公開](https://www.publickey1.jp/2025/ms-agent-framework-prev01.png)

マイクロソフトは、MCP（Model Context Protocol）や A2A（Agent to Agent）プロトコルなどの業界標準に対応した AI エージェントや、複数の AI エージェントのオーケストレーションの開発を容易にする「Micro...

---

## ローカル LLM

## その他 LLM 関連

# 注目トピック

## AI コーディング

### [Claude Code on the web を触ってみた](https://zenn.dev/beagle/articles/bc6ef88dd68615)

![Claude Code on the webを触ってみた](https://res.cloudinary.com/zenn/image/upload/s--PQtJfEpy--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%2520on%2520the%2520web%25E3%2582%2592%25E8%25A7%25A6%25E3%2581%25A3%25E3%2581%25A6%25E3%2581%25BF%25E3%2581%259F%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%25B3%25E3%2583%25BC%25E3%2581%2590%25E3%2582%258B%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2FkMjNkMTdmZTkuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Claude Code on the Web の仕様を徹底解剖](https://zenn.dev/oikon/articles/claude-code-web-sandbox)

![Claude Code on the Webの仕様を徹底解剖](https://res.cloudinary.com/zenn/image/upload/s--Ea8Y9bes--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%2520on%2520the%2520Web%25E3%2581%25AE%25E4%25BB%2595%25E6%25A7%2598%25E3%2582%2592%25E5%25BE%25B9%25E5%25BA%2595%25E8%25A7%25A3%25E5%2589%2596%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Oikon%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzYyMTkzODY4NjUuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Claude Code のサンドボックス機能を試してみた](https://azukiazusa.dev/blog/claude-code-sandbox-feature/)

![Claude Code のサンドボックス機能を試してみた](https://azukiazusa.dev/blog/ogp/claude-code-sandbox-feature.png)

Claude Code をはじめとする AI コーディングエージェントは、コマンドを実行するたびにユーザーの承認を求める仕組みが備わっていますが、これには開発サイクルの低下や承認疲れといった問題があります。Claude Code のサンドボックス機能は、ファイルシステムやネットワークへのアクセスを制限し、安全に動作させるための仕組みです。この記事では、Claude Code のサンドボックス機能の仕組みと利用方法について解説します。

---

### [Claude を"育てる"新常識！ Agent Skills 徹底解説 - あなたの仕事を自動化する魔法のレシピ ✨ ｜ Kyutaro](https://note.com/kyutaro15/n/nfcc15522626f?sub_rt=share_sb)

![Claudeを"育てる"新常識！ Agent Skills徹底解説 - あなたの仕事を自動化する魔法のレシピ ✨｜Kyutaro](https://assets.st-note.com/production/uploads/images/222783048/rectangle_large_type_2_a0a019bd0aacd23127f022921615c836.png?fit=bounds&quality=85&width=1280)

属人化をやめたい。品質を揃えたい。スピードは落とさない。 Agent Skills は、現場のノウハウを「再現可能な資産」に変えます。プロンプトではなく標準手順 × コードで積み上げるから、新人でもベテランと同じ結果に。それを実現するのが、Anthropic の画期的な機能、「Agent Skills」です。 この記事は、導入判断に必要な安全性・運用設計・環境別のリスクと効率、そして即導入できるサンプルまで一気通貫で解説し、あなたが今日からでも「AI を育てる」ための、実践的な設計図を提供します。 1. そもそも Agent Skills って何？ - AI の新しい「引き出し」術 🗄️ A

---

### [X ユーザーの Oikon さん: 「Claude Skills ちょっと分かってきた。 Skills の情報を外に出して概要のみを保持することで、コンテキストの消費量を削減するだけでなく、効率的にツールを利用が出来る機能。 ① Skills の概要 (YAML 形式のメタデータ) ② Skills の中身 ③ Skills に付随する追加情報 ① -&gt; ② (-&gt; ③) https://t.co/fOdNzCyuU0」 / X](https://x.com/oikon48/status/1979014705617473650)

![XユーザーのOikonさん: 「Claude Skills ちょっと分かってきた。  Skillsの情報を外に出して概要のみを保持することで、コンテキストの消費量を削減するだけでなく、効率的にツールを利用が出来る機能。  ① Skillsの概要 (YAML形式のメタデータ) ② Skillsの中身 ③ Skillsに付随する追加情報  ① -> ② (-> ③) https://t.co/fOdNzCyuU0」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [Claude Code Subagents 再入門 ~cc-sdd の実装で学んだこと~](https://speakerdeck.com/gotalab555/claude-code-subagents-zai-ru-men-cc-sddnoshi-zhuang-dexue-ndakoto)

![Claude Code Subagents 再入門 ~cc-sddの実装で学んだこと~](https://files.speakerdeck.com/presentations/cd4536704070441ebe1c7a48d64ad0c0/slide_0.jpg?37007375)

Claude Code の Subagents を再入門。Subagents が独自のコンテキストウィンドウを利用するために起きるコンテキスト損失という落とし穴を軸に、READ 系の適材適所、Write 系の設計注意、エージェント数の最小化と明確な description、巨大文脈のファイル委任、Task ツールのログ&hellip;

---

### [MCP ツール棚卸しによる Claude Code のコンテキスト最適化](https://zenn.dev/medley/articles/optimizing-claude-code-context-with-mcp-tool-audit)

![MCPツール棚卸しによるClaude Codeのコンテキスト最適化](https://res.cloudinary.com/zenn/image/upload/s--NiTuF-zW--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:MCP%25E3%2583%2584%25E3%2583%25BC%25E3%2583%25AB%25E6%25A3%259A%25E5%258D%25B8%25E3%2581%2597%25E3%2581%25AB%25E3%2582%2588%25E3%2582%258BClaude%2520Code%25E3%2581%25AE%25E3%2582%25B3%25E3%2583%25B3%25E3%2583%2586%25E3%2582%25AD%25E3%2582%25B9%25E3%2583%2588%25E6%259C%2580%25E9%2581%25A9%25E5%258C%2596%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Yuta%2520Takahashi%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzU5YTVhMjE3YTguanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E6%25A0%25AA%25E5%25BC%258F%25E4%25BC%259A%25E7%25A4%25BE%25E3%2583%25A1%25E3%2583%2589%25E3%2583%25AC%25E3%2583%25BC%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzYzOTI2MjI2ZTUuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [X ユーザーの Oikon さん: 「Anthropic のエンジニアの登壇 【Mastering Claude Code】 ・AI に理解してもらえるようドキュメントの更新は重要 ・Claude Core からの通知をオンにするのは、最初の設定の一歩としてオススメ ・文字起こし機能をオンにするのもオススメ ・CI/CD パイプラインで Claude GitHub Actions を使う https://t.co/Qm6afKe45w」 / X](https://x.com/oikon48/status/1984110545470099907)

![XユーザーのOikonさん: 「Anthropicのエンジニアの登壇  【Mastering Claude Code】  ・AIに理解してもらえるようドキュメントの更新は重要 ・Claude Core からの通知をオンにするのは、最初の設定の一歩としてオススメ ・文字起こし機能をオンにするのもオススメ ・CI/CDパイプラインでClaude GitHub Actionsを使う https://t.co/Qm6afKe45w」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

## MCP

## AI エージェント

### [LangGraph と NeMo Agent Toolkit ではじめる ReAct エージェント](https://developer.nvidia.com/ja-jp/blog/practical-tutorial-on-react-langgraph-nemo-agent-toolkit/)

![LangGraph と NeMo Agent Toolkit ではじめる ReAct エージェント](https://developer-blogs.nvidia.com/ja-jp/wp-content/uploads/sites/6/2025/10/llm-social-chat-labs-blog-5-tw-1200x675-1-660x370.jpg)

AI エージェントの概念を簡潔に解説し、特に「ReAct (Reasoning and Acting) エージェント」に焦点を当てて、その仕組みと実装方法について詳しく説明します。

---

## ロボティクス

## 気になるツール/サービス 1(開発/情報系)

### [X ユーザーのまさお@AI 駆動開発さん: 「🚨 コーディングの常識、変わりつつあります 本日 AI エディタ『Cursor 2.0』が正式に公開されました！ これは開発者の仕事を根底から変えつつあります… 細かい実装は AI に任せ「何を作るか」に集中できる Agent 中心の設計へ進化 押さえておきたい内容をまとめました 👇 https://t.co/n9Ok3wMQ4V」 / X](https://x.com/AI_masaou/status/1983675140362862887)

![Xユーザーのまさお@AI駆動開発さん: 「🚨 コーディングの常識、変わりつつあります  本日 AIエディタ『Cursor 2.0』が正式に公開されました！  これは開発者の仕事を根底から変えつつあります…    細かい実装はAIに任せ「何を作るか」に集中できるAgent中心の設計へ進化  押さえておきたい内容をまとめました👇 https://t.co/n9Ok3wMQ4V」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [X ユーザーのオカムラ | 株式会社メイク・ア・チェンジさん: 「Cursor 2.0 の Browser 機能すごい。エレメントを指定して指示できるので UI 修正がはかどる。 以下の手順ですぐに試せます。 ①Cursor チャット欄の Web アイコン（地球アイコン？）から「Browser Tab」を選択 ② アドレスバーに URL（http://localhost:5173/ など）を入力 ③ Browser Tab の右上の「Select https://t.co/o3OaISr7kV」 / X](https://x.com/masa_oka108/status/1984927616097534261)

![Xユーザーのオカムラ | 株式会社メイク・ア・チェンジさん: 「Cursor 2.0 のBrowser機能すごい。エレメントを指定して指示できるのでUI修正がはかどる。  以下の手順ですぐに試せます。  ①Cursorチャット欄のWebアイコン（地球アイコン？）から「Browser Tab」を選択  ②アドレスバーにURL（http://localhost:5173/ など）を入力  ③ Browser Tabの右上の「Select https://t.co/o3OaISr7kV」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

## 気になるツール/サービス 2(画像/動画/3D/音声/音楽生成、認識技術、XR/ゲーム関連等)

### [X ユーザーのすぐる | ChatGPT ガチ勢 𝕏 さん: 「Alibaba が公開した「Wan2.2」の ディープフェイク技術がすごいな…。 https://t.co/AjeVYhGnKJ 自分が話している動画と、同じレンズで撮影した誰かの写真さえあれば「顔出しせず」にその人物として動画出演が可能になる。」 / X](https://x.com/SuguruKun_ai/status/1983874423997235255)

![Xユーザーのすぐる | ChatGPTガチ勢 𝕏さん: 「Alibabaが公開した「Wan2.2」の ディープフェイク技術がすごいな…。 https://t.co/AjeVYhGnKJ 自分が話している動画と、同じレンズで撮影した誰かの写真さえあれば「顔出しせず」にその人物として動画出演が可能になる。」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

## その他

### [なぜバイブコーディングをめぐる議論は噛み合わないのか](https://zenn.dev/shintake/articles/cc4779fb80dea7)

![なぜバイブコーディングをめぐる議論は噛み合わないのか](https://res.cloudinary.com/zenn/image/upload/s--VHL1JDWM--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E3%2581%25AA%25E3%2581%259C%25E3%2583%2590%25E3%2582%25A4%25E3%2583%2596%25E3%2582%25B3%25E3%2583%25BC%25E3%2583%2587%25E3%2582%25A3%25E3%2583%25B3%25E3%2582%25B0%25E3%2582%2592%25E3%2582%2581%25E3%2581%2590%25E3%2582%258B%25E8%25AD%25B0%25E8%25AB%2596%25E3%2581%25AF%25E5%2599%259B%25E3%2581%25BF%25E5%2590%2588%25E3%2582%258F%25E3%2581%25AA%25E3%2581%2584%25E3%2581%25AE%25E3%2581%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:shintake%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUNnOG9jTDBvaE01ZERCWDhCM3dkTTVvaW1nLTZqZWtUNHlHdVA5YW15OGM3ME1GN0RSNnNBPXM5Ni1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Claude Code 導入 3 ヶ月後の社内アンケートから分かったこと](https://zenn.dev/readyfor_blog/articles/a1cfd81a562e07)

![Claude Code導入3ヶ月後の社内アンケートから分かったこと](https://res.cloudinary.com/zenn/image/upload/s--mjaA3Zfm--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E5%25B0%258E%25E5%2585%25A53%25E3%2583%25B6%25E6%259C%2588%25E5%25BE%258C%25E3%2581%25AE%25E7%25A4%25BE%25E5%2586%2585%25E3%2582%25A2%25E3%2583%25B3%25E3%2582%25B1%25E3%2583%25BC%25E3%2583%2588%25E3%2581%258B%25E3%2582%2589%25E5%2588%2586%25E3%2581%258B%25E3%2581%25A3%25E3%2581%259F%25E3%2581%2593%25E3%2581%25A8%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:resqnet%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2E4NzU2YzZmODkuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:READYFOR%25E3%2583%2586%25E3%2583%2583%25E3%2582%25AF%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2pPSm1Xd01qOGxqcUhGRlh0ZEZSRnZGNU1sbERONjRCMV9NdjlQckE9czI1MC1j%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---
