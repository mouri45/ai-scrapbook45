# このページについて

- 2025/12/09 から 2026/01/09 の期間で、個人的に気になった AI ニュース/記事/ポストなどまとめたページです。
- TechFirst Leaders の社内 AI 勉強会用に整理したものを公開しています。
- Web 開発/システム開発エンジニア寄りの視点でまとめています。
- まとめた人：[@mouri45](https://x.com/mouri45)

# 気になるトピック

- 所感的に Claude Code が AI 駆動開発をしてる人たちから圧倒的に指示を得てる感じ。
- Anthropic が Agent Skills の仕様を公開し、VS Code や Cursor などのサードパーティがサポート。MCP の簡易版のような位置付けだが、MCP が盛り上がった時以上に界隈が盛り上がってる感じ。
- Claude Code のコンテキストウィンドウを有効に使う TIPS をよく見かけた。
- Claude Code の書籍が２冊発売。

# カテゴリ

**AI 企業/LLM 関連ニュース**：[OpenAI](#openai) | [Google](#google) | [Anthropic](#anthropic) | [MS/GitHub](#msgithub) | [Amazon](#amazon) | [ローカル LLM](#ローカル-llm) | [その他 LLM 関連](#その他-llm-関連)

**注目トピック**：[AI 駆動開発](#ai-駆動開発) | [Skills/MCP](#skillsmcp) | [AI エージェント](#ai-エージェント) | [ローカル LLM](#ローカル-llm) | [ロボティクス](#ロボティクス) | [その他 AI 利用 TIPS](#その他ai利用tips)

**ツール/サービス**：[開発/情報系](#気になるツールサービス-1開発情報系) | [画像/動画/3D 等](#気になるツールサービス-2画像動画3d音声音楽生成認識技術xrゲーム関連等) | [その他](#その他)

# AI 企業/LLM 関連ニュース

## OpenAI

### [OpenAI、画像生成モデル「GPT Image 1.5」を発表 ～「ChatGPT」に写真加工ページも／従来より最大 4 倍の速さ、ディテールを保ったまま指示通りに画像の生成・編集](https://forest.watch.impress.co.jp/docs/news/2071942.html)

![OpenAI、画像生成モデル「GPT Image 1.5」を発表 ～「ChatGPT」に写真加工ページも／従来より最大4倍の速さ、ディテールを保ったまま指示通りに画像の生成・編集](https://forest.watch.impress.co.jp/img/wf/list/2071/942/open_ai.jpg)

米 OpenAI は 12 月 16 日（現地時間）、新しい画像生成モデルのフラグシップ「GPT Image 1.5」を発表した。「ChatGPT Images」（chatgpt.com/images/）のバックエンドとして採用されており、ディテールを保ったまま指示通りに画像の生成・編集が行えるほか、生成速度も最大 4 倍にまで高められているという。

---

### [GPT Image 1.5 プロンプトガイド｜ npaka](https://note.com/npaka/n/n454c5579125d?sub_rt=share_sb)

![GPT Image 1.5 プロンプトガイド｜npaka](https://assets.st-note.com/production/uploads/images/236873202/rectangle_large_type_2_b1b956832dbf0440bf3fffe2063e743c.png?fit=bounds&quality=85&width=1280)

以下の記事が面白かったので、簡単にまとめました。 ・Gpt-image-1.5 Prompting Guide 1. はじめに 「gpt-image-1.5」は、プロダクション品質のビジュアル生成と、高度に制御可能なクリエイティブワークフローを実現する最新の画像生成モデルです。 リアリティ・正確性・編集耐性の各面で大幅な進化を遂げており、プロフェッショナルなデザイン業務から反復的なコンテンツ制作まで、幅広い用途に適しています。前世代モデルと比べて視覚品質が大きく向上しているだけでなく、高品質レンダリングと低レイテンシ生成の両方をサポートします。 主な機能は、次のとおりです

---

## Google

### [「Gemini 3」の新ファミリー「Gemini 3 Flash」登場、日常用に最適な性能・コストバランス／「Gemini」アプリの既定モデルに。前代旗艦モデル「Gemini 2.5 Pro」より 3 倍高速かつ安価](https://forest.watch.impress.co.jp/docs/news/2072258.html)

![「Gemini 3」の新ファミリー「Gemini 3 Flash」登場、日常用に最適な性能・コストバランス／「Gemini」アプリの既定モデルに。前代旗艦モデル「Gemini 2.5 Pro」より3倍高速かつ安価](https://forest.watch.impress.co.jp/img/wf/list/2072/258/image1.png)

米 Google は 12 月 17 日（現地時間）、「Gemini 3」ファミリーの新しいモデル 「Gemini 3 Flash」 を発表した。高速かつ低コストで、効率性に特化した設計となっている。

---

### [Google、Gemini などとやり取りできる「Interactions API」β 版公開](https://codezine.jp/news/detail/22787)

![Google、Geminiなどとやり取りできる「Interactions API」β版公開](https://codezine.jp/static/images/article/22787/gemini.png)

---

### [Google が「Gemini Deep Research エージェント」を発表 自律的調査機能を強化](https://www.sbbit.jp/article/cont1/177006)

![Googleが「Gemini Deep Researchエージェント」を発表 自律的調査機能を強化](https://www.sbbit.jp/article/image/177006/OGP_bit202512140816405739.png)

Google は 2025 年 12 月 11 日（米国時間）、同社の生成 AI プラットフォーム「Gemini」を進化させる新たな AI エージェント機能として 「Gemini Deep Research（ディープリサーチ）エージェント」 を発表した。これは大規模言語モデル「Gemini 3 Pro」を推論コアとして採用し、複雑な調査タスクを自律的に実行・統合レポートを生成できるよう設計された高度な AI エージェントである。

---

### [Interactions API × Deep Research Agent 入門：Google が描く「自律型エージェント」の未来](https://zenn.dev/google_cloud_jp/articles/4d04c72142b8f1)

![Interactions API × Deep Research Agent 入門：Google が描く「自律型エージェント」の未来](https://res.cloudinary.com/zenn/image/upload/s--ctZW3MJ9--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Interactions%2520API%2520%25C3%2597%2520Deep%2520Research%2520Agent%2520%25E5%2585%25A5%25E9%2596%2580%25EF%25BC%259AGoogle%2520%25E3%2581%258C%25E6%258F%258F%25E3%2581%258F%25E3%2580%258C%25E8%2587%25AA%25E5%25BE%258B%25E5%259E%258B%25E3%2582%25A8...%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Yuting%2520Lin%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzA1OTIyZmJmYTMuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:Google%2520Cloud%2520Japan%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzllNzg0NTYxOGQuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Google、MCP サーバの発見や管理のためのレジストリ「Cloud API Registry」プレビュー公開](https://www.publickey1.jp/blog/25/googlemcpcloud_api_registry.html)

![Google、MCPサーバの発見や管理のためのレジストリ「Cloud API Registry」プレビュー公開](https://www.publickey1.jp/2025/7sKjk-RW.jpg)

Google は、Google や社内で提供されている MCP（Model Context Protocol）サーバや関連ツールの発見、管理、利用、監視などを統合的に可能にするレジストリサービス「Cloud API Registry」のプレビュー...

---

### [Google、音声生成モデル「Gemini 2.5 Flash Native Audio」をアップデート／指示に忠実、より自然なやりとりを実現。ライブ音声翻訳など自社製品でも活用](https://forest.watch.impress.co.jp/docs/news/2071296.html)

![Google、音声生成モデル「Gemini 2.5 Flash Native Audio」をアップデート／指示に忠実、より自然なやりとりを実現。ライブ音声翻訳など自社製品でも活用](https://forest.watch.impress.co.jp/img/wf/list/2071/296/image1.png)

米 Google は 12 月 12 日（現地時間）、ライブ音声エージェント向けに最適化された AI モデル「Gemini 2.5 Flash Native Audio」のアップデートを発表した。「Google AI Studio」や「Vertex AI」といった AI ツール・プラットフォームで展開されるほか、「Gemini Live」や「Search Live」（日本未提供）といった検索エクスペリエンスにも活用されるという。

---

### [Gemini 2.5 Flash Native Audio の概要｜ npaka](https://note.com/npaka/n/n78b9a1a0ce0f)

![Gemini 2.5 Flash Native Audio の概要｜npaka](https://assets.st-note.com/production/uploads/images/236123364/rectangle_large_type_2_6708d0068ed933101947dc99d3ca7853.png?fit=bounds&quality=85&width=1280)

以下の記事が面白かったので、簡単にまとめました。 ・Improved Gemini audio models for powerful voice interactions 1. Gemini 2.5 Flash Native Audio 本日、ライブ音声エージェント向けにアップデートされた「Gemini 2.5 Flash Native Audio」をリリースしました。複雑なワークフローの処理、ユーザー指示への対応、自然な会話の実現といったモデルの能力が向上します。 「Gemini 2.5 Flash Native Audio」は、「Google AI Studio」「

---

## Anthropic

### [Anthropic、AI エージェントにタスクの手順や知識を組み込める「Agent Skills」をオープンスタンダードに。早くも VS Code や Cursor などがサポート](https://www.publickey1.jp/blog/25/anthropicaiagent_skillsvs_codecursor.html)

![Anthropic、AIエージェントにタスクの手順や知識を組み込める「Agent Skills」をオープンスタンダードに。早くもVS CodeやCursorなどがサポート](https://www.publickey1.jp/2025/agentskills04.png)

Anthropic は、同社の AI サービス「Claude」が備えてきた機能「Skills」を業界のオープンスタンダードにすべく「Agent Skills」仕様の公開を発表しました。 Agent Skills は、AI エージェントにタスクごとの手...

---

### [Claude Code の LSP サポート](https://azukiazusa.dev/blog/claude-code-lsp-support/)

![Claude Code の LSP サポート](https://azukiazusa.dev/blog/ogp/claude-code-lsp-support.png)

Claude Code のバージョン 2.0.74 から LSP（Language Server Protocol）サポートが追加されました。LSP サポートにより、Claude Code はコードベースに対してシンボルの定義検索、参照検索、ホバー情報の取得などの操作が可能になります。この記事では Claude Code の LSP サポートの概要と使用方法を紹介します。

---

### [【2026/1/8 最新アプデ】Claude Code 2.1.0 の重要変更点を触ってみた](https://zenn.dev/canly/articles/85f77e212b084a)

![【2026/1/8最新アプデ】Claude Code 2.1.0の重要変更点を触ってみた](https://res.cloudinary.com/zenn/image/upload/s--pgH1o33p--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E3%2580%25902026%252F1%252F8%25E6%259C%2580%25E6%2596%25B0%25E3%2582%25A2%25E3%2583%2597%25E3%2583%2587%25E3%2580%2591Claude%2520Code%25202.1.0%25E3%2581%25AE%25E9%2587%258D%25E8%25A6%2581%25E5%25A4%2589%25E6%259B%25B4%25E7%2582%25B9%25E3%2582%2592%25E8%25A7%25A6%25E3%2581%25A3%25E3%2581%25A6%25E3%2581%25BF%25E3%2581%259F%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:ryu%2520fukuda%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2EwYjI3NWVjYTkuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E3%2582%25AB%25E3%2583%25B3%25E3%2583%25AA%25E3%2583%25BC%25E3%2583%2586%25E3%2583%2583%25E3%2582%25AF%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzdmNWE3ZGIyYWIuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Claude Code に Slack でコーディングタスクを依頼可能に。Anthropic がリサーチプレビュー公開](https://www.publickey1.jp/blog/25/claude_codeslackanthropic.html)

![Claude CodeにSlackでコーディングタスクを依頼可能に。Anthropicがリサーチプレビュー公開](https://www.publickey1.jp/2025/claudecode4slack-b03.png)

Claude Code を提供する Anthropic は、Claude と Slack を連携させる「Claude app for Slack」の機能を拡張し、Claude Code に対して Slack でデバッグ作業やコードレビューなどを依頼可能にする...

---

### [Amazon.co.jp: 実践 Claude Code 入門―現場で活用するための AI コーディングの思考法 エンジニア選書 eBook : 西見 公宏, 吉田 真吾, 大嶋 勇樹: Kindle ストア](https://www.amazon.co.jp/dp/B0G4NVX1NF)

Amazon.co.jp: 実践 Claude Code 入門―現場で活用するための AI コーディングの思考法 エンジニア選書 eBook : 西見 公宏, 吉田 真吾, 大嶋 勇樹: Kindle ストア

---

### [Amazon.co.jp: Claude Code による AI 駆動開発入門 eBook : 平川 知秀: Kindle ストア](https://www.amazon.co.jp/dp/B0G13D2JS4)

Amazon.co.jp: Claude Code による AI 駆動開発入門 eBook : 平川 知秀: Kindle ストア

---

## MS/GitHub

## ローカル LLM

## その他 LLM 関連

# 注目トピック

## AI 駆動開発

### [Claude Code のコンテキストウィンドウを完全に理解する | gihyo.jp](https://gihyo.jp/article/2025/12/get-started-claude-code-05)

![Claude Codeのコンテキストウィンドウを完全に理解する | gihyo.jp](https://gihyo.jp/assets/images/article/2025/12/get-started-claude-code-05/context-command.png)

「Claude Code」は、CLI 上で動く LLM による AI エージェントツールです。この記事は 12 月 5 日に発売された『Claude Code による AI 駆動開発入門』に書ききれなかった応用的な内容や最新のアップデートについて解説します。

---

### [Claude Code のコンテキストを節約する](https://zenn.dev/karaage0703/articles/1f30a572ff8460)

![Claude Codeのコンテキストを節約する](https://res.cloudinary.com/zenn/image/upload/s--AQIpPd4p--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AE%25E3%2582%25B3%25E3%2583%25B3%25E3%2583%2586%25E3%2582%25AD%25E3%2582%25B9%25E3%2583%2588%25E3%2582%2592%25E7%25AF%2580%25E7%25B4%2584%25E3%2581%2599%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%258B%25E3%2582%2589%25E3%2581%2582%25E3%2581%2592%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2hDZEtvakJfZXdDTjNCV1Z0WXIteFNIZ0hmRjlXZmt3QzI5c0Y0aXYwPXMyNTAtYw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Claude Code ですぐ制限にかからないようにするコツ](https://zenn.dev/aun_phonogram/articles/4be2f4745726fb)

![Claude Codeですぐ制限にかからないようにするコツ](https://res.cloudinary.com/zenn/image/upload/s--bpMrIbNq--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25A7%25E3%2581%2599%25E3%2581%2590%25E5%2588%25B6%25E9%2599%2590%25E3%2581%25AB%25E3%2581%258B%25E3%2581%258B%25E3%2582%2589%25E3%2581%25AA%25E3%2581%2584%25E3%2582%2588%25E3%2581%2586%25E3%2581%25AB%25E3%2581%2599%25E3%2582%258B%25E3%2582%25B3%25E3%2583%2584%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:%25E5%2590%2589%25E5%25B2%25A1%25E8%25A3%2595%25E8%25B2%25B4%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzUwM2RkNmMyMzkuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:AUN%2520Tech%2520Blog%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzFmNzI5YzVhODEuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Claude Code のビルドインツールは無効化してシステムプロンプトを削減できる](https://zenn.dev/sqer/articles/5c52615eeabce0)

![Claude Codeのビルドインツールは無効化してシステムプロンプトを削減できる](https://res.cloudinary.com/zenn/image/upload/s--2el5bTbV--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AE%25E3%2583%2593%25E3%2583%25AB%25E3%2583%2589%25E3%2582%25A4%25E3%2583%25B3%25E3%2583%2584%25E3%2583%25BC%25E3%2583%25AB%25E3%2581%25AF%25E7%2584%25A1%25E5%258A%25B9%25E5%258C%2596%25E3%2581%2597%25E3%2581%25A6%25E3%2582%25B7%25E3%2582%25B9%25E3%2583%2586%25E3%2583%25A0%25E3%2583%2597%25E3%2583%25AD%25E3%2583%25B3%25E3%2583%2597%25E3%2583%2588%25E3%2582%2592%25E5%2589%258A%25E6%25B8%259B%25E3%2581%25A7%25E3%2581%258D%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:hikae%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzExZjM4ZmUxNGMuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Context is King？ 〜Verifiability 時代とコンテキスト設計 / Beyond "Context is King"](https://speakerdeck.com/rkaga/beyond-context-is-king)

![Context is King？  〜Verifiability時代とコンテキスト設計 / Beyond "Context is King"](https://files.speakerdeck.com/presentations/66f8c93772744e8c81f870936efcfd57/slide_0.jpg?37698905)

2025/12/11(木)開催の、「成果に繋がる AI エージェント活用の第一歩 - AI 猛者たちが実践する "コンテキスト設計術"」の登壇スライドです。
https://explaza.connpass.com/event/376388/

---

### [Claude Code の開発者による Claude Code 活用術がめちゃくちゃ有用そう](https://zenn.dev/explaza/articles/a387d2bf1cb448)

![Claude Codeの開発者によるClaude Code活用術がめちゃくちゃ有用そう](https://res.cloudinary.com/zenn/image/upload/s--dRfkj0I---/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AE%25E9%2596%258B%25E7%2599%25BA%25E8%2580%2585%25E3%2581%25AB%25E3%2582%2588%25E3%2582%258BClaude%2520Code%25E6%25B4%25BB%25E7%2594%25A8%25E8%25A1%2593%25E3%2581%258C%25E3%2582%2581%25E3%2581%25A1%25E3%2582%2583%25E3%2581%258F%25E3%2581%25A1%25E3%2582%2583%25E6%259C%2589%25E7%2594%25A8%25E3%2581%259D%25E3%2581%2586%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:%25E3%2582%25A6%25E3%2583%25B3%25E3%2582%25B9%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzQzOWQzZGM0MGMuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/g_south_west%2Ch_34%2Cl_default:og-publication-pro-mark-xcosax%2Cw_34%2Cx_217%2Cy_158/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E6%25A0%25AA%25E5%25BC%258F%25E4%25BC%259A%25E7%25A4%25BE%25E3%2582%25A8%25E3%2582%25AF%25E3%2582%25B9%25E3%2583%2597%25E3%2583%25A9%25E3%2582%25B6%2Cx_255%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzVlZmYzMTA2MDQuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Advent of Claude: 31 Days of Claude Code — adocomplete — Ado Kukic](https://adocomplete.com/advent-of-claude-2025/)

![Advent of Claude: 31 Days of Claude Code — adocomplete — Ado Kukic](https://cdn.adocomplete.com/og/posts/advent-of-claude-2025/og-image.png)

A comprehensive guide to Claude Code's most powerful features, from quick shortcuts to advanced agent patterns.

---

### [Claude Code アドベントカレンダー: 24 Tips まとめ](https://zenn.dev/oikon/articles/cc-advent-calendar)

![Claude Codeアドベントカレンダー: 24 Tipsまとめ](https://res.cloudinary.com/zenn/image/upload/s--LIcZX3p6--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2582%25A2%25E3%2583%2589%25E3%2583%2599%25E3%2583%25B3%25E3%2583%2588%25E3%2582%25AB%25E3%2583%25AC%25E3%2583%25B3%25E3%2583%2580%25E3%2583%25BC%253A%252024%2520Tips%25E3%2581%25BE%25E3%2581%25A8%25E3%2582%2581%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Oikon%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzYyMTkzODY4NjUuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Claude Code の全ての CHANGELOG を追ってきて](https://zenn.dev/oikon/articles/claude-code-2025)

![Claude Codeの全てのCHANGELOGを追ってきて](https://res.cloudinary.com/zenn/image/upload/s--ADJuubBR--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AE%25E5%2585%25A8%25E3%2581%25A6%25E3%2581%25AECHANGELOG%25E3%2582%2592%25E8%25BF%25BD%25E3%2581%25A3%25E3%2581%25A6%25E3%2581%258D%25E3%2581%25A6%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Oikon%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzYyMTkzODY4NjUuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Anthropic Courses](https://anthropic.skilljar.com/)

![Anthropic Courses](https://cdn.sanity.io/images/4zrzovbb/website/c4bd33e7c8e809a2f9a9a5896ee13961e2a738ec-2400x1260.png)

Learn to build with Claude through Anthropic's comprehensive courses and training programs.

---

### [X ユーザーの ML_Bear さん: 「Claude Code の Tips を 40 個以上集めたレポジトリ。長すぎて全部見れてない＆基礎的なものが結構多い印象があったけど、意外と見落としてた Tips あるのでざっと目を通してみるのもいいかも？ https://t.co/n995b6ReZJ」 / X](https://x.com/MLBear2/status/2008023267471507578)

![XユーザーのML_Bearさん: 「Claude Code の Tips を40個以上集めたレポジトリ。長すぎて全部見れてない＆基礎的なものが結構多い印象があったけど、意外と見落としてたTipsあるのでざっと目を通してみるのもいいかも？  https://t.co/n995b6ReZJ」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [X ユーザーの kaya さん: 「Anthropic エンジニアによる、Claude Agent SDK の 2 時間ワークショップが公開されました 後で見る人向けに、学んだことをツリーでまとめます Claude Code の開発経験から得られたエージェント構築の設計思想と実践 TIPS が詰まってます https://t.co/Z1SoOwmkJY」 / X](https://x.com/Ka888aa/status/2008340819090997424)

![Xユーザーのkayaさん: 「Anthropicエンジニアによる、Claude Agent SDKの2時間ワークショップが公開されました  後で見る人向けに、学んだことをツリーでまとめます  Claude Codeの開発経験から得られたエージェント構築の設計思想と実践TIPSが詰まってます https://t.co/Z1SoOwmkJY」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [Claude Code 完全ガイド - 基礎から高度なカスタマイズまで](https://zenn.dev/tmasuyama1114/books/claude_code_basic)

![Claude Code 完全ガイド - 基礎から高度なカスタマイズまで](https://res.cloudinary.com/zenn/image/upload/s--Rnq3sWVc--/g_center%2Ch_280%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYm9va19jb3Zlci9lMWY1NGUzYmRiLnBuZw==%2Cw_200/v1627283836/default/og-base-book_yz4z02.jpg?_a=BACAGSGT)

こんにちは、とまだです。

「Claude Code をインストールしたけど、使いこなせている気がしない」
「CLAUDE.md って結局どう書けばいいの？」
「Hooks？MCP？カスタムコマンド？何から始めればいい？」

そんな疑問を全て解消する、Claude Code の "辞書

---

### [X ユーザーの Oikon さん: 「Claude Code 2.0.72 から Chrome が操作できるようになりました。 /chrome コマンドで Status と Extension が有効になっていることを確認した上で、ブラウザ操作をお願いすると、MCP ツール(mcp**claude-in-chrome**) を使用してブラウザを操作してくれます。 claude --chrome でも有効にできます。 https://t.co/rqXMuEaqXu」 / X](https://x.com/oikon48/status/2001451347380703258)

![XユーザーのOikonさん: 「Claude Code 2.0.72 から Chromeが操作できるようになりました。  /chrome コマンドでStatusとExtensionが有効になっていることを確認した上で、ブラウザ操作をお願いすると、MCPツール(mcp__claude-in-chrome__) を使用してブラウザを操作してくれます。  claude --chrome でも有効にできます。 https://t.co/rqXMuEaqXu」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [Claude Code 公式 Plugin のすすめ](https://zenn.dev/modokkin/articles/zenn-2025-12-03-tech-claude-code-plugins)

![Claude Code公式Pluginのすすめ](https://res.cloudinary.com/zenn/image/upload/s--GPdT_1ss--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E5%2585%25AC%25E5%25BC%258FPlugin%25E3%2581%25AE%25E3%2581%2599%25E3%2581%2599%25E3%2582%2581%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%25AF%25E3%2581%25B6%25E3%2581%25A1%25E3%2582%2593%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2Q4ZDhlMmQyZTAuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Claude Code にテストで楽をさせない技術](https://speakerdeck.com/beagle_dog_inu/claude-codenitesutodele-wosasenaiji-shu)

![Claude Codeにテストで楽をさせない技術](https://files.speakerdeck.com/presentations/39b955f8c60d43f3b4fde12be768948a/slide_0.jpg?37832160)

Claude Code Meetup Tokyo LT 登壇資料

---

### [X ユーザーの nogu さん: 「Anthropic 公式メンバーの Thariq 氏が公開した「仕様ベース開発」の手法 最小限の仕様またはプロンプトを入力 ↓ AskUserQuestionTool を使ってインタビューを依頼 ↓ 仕様を実行するための新しいセッションを作成 大規模な機能だと、40 以上の質問をしてくるので詳細な仕様書ができあがるらしい https://t.co/UgJZTKoS2l」 / X](https://x.com/_nogu66/status/2005645420744318984)

![Xユーザーのnoguさん: 「Anthropic公式メンバーのThariq氏が公開した「仕様ベース開発」の手法  最小限の仕様またはプロンプトを入力 ↓ AskUserQuestionToolを使ってインタビューを依頼 ↓ 仕様を実行するための新しいセッションを作成  大規模な機能だと、40以上の質問をしてくるので詳細な仕様書ができあがるらしい https://t.co/UgJZTKoS2l」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [Claude Code on the web と CLI 間でのタスクの移動について](https://zenn.dev/beagle/articles/_0016_claude_code_session_cli_and_web)

![Claude Code on the webとCLI間でのタスクの移動について](https://res.cloudinary.com/zenn/image/upload/s--6GGxFzDE--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%2520on%2520the%2520web%25E3%2581%25A8CLI%25E9%2596%2593%25E3%2581%25A7%25E3%2581%25AE%25E3%2582%25BF%25E3%2582%25B9%25E3%2582%25AF%25E3%2581%25AE%25E7%25A7%25BB%25E5%258B%2595%25E3%2581%25AB%25E3%2581%25A4%25E3%2581%2584%25E3%2581%25A6%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%25B3%25E3%2583%25BC%25E3%2581%2590%25E3%2582%258B%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2FkMjNkMTdmZTkuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [X ユーザーのぬこぬこ | NUKO さん: 「Claude Code のフックの解説記事 セッション開始から終了まで全段階、計 8 種類を用意。フォーマッターの自動実行、危険なコマンドの停止、テストの自動承認、動的なコンテキスト注入など反復作業を削減、プロジェクトルールを自動で反映。 https://t.co/21OUKK5dsL」 / X](https://x.com/nukonuko/status/1999224138305851656)

![Xユーザーのぬこぬこ | NUKOさん: 「Claude Code のフックの解説記事  セッション開始から終了まで全段階、計 8 種類を用意。フォーマッターの自動実行、危険なコマンドの停止、テストの自動承認、動的なコンテキスト注入など反復作業を削減、プロジェクトルールを自動で反映。 https://t.co/21OUKK5dsL」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [【アーカイブ】Oikon× 平川知秀　 ClaudeCode 座談会（2025 年 12 月 23 日開催）](https://www.youtube.com/watch?v=WKgga6EP8cQ)

![【アーカイブ】Oikon×平川知秀　ClaudeCode座談会（2025年12月23日開催）](https://i.ytimg.com/vi/WKgga6EP8cQ/hqdefault.jpg)

0:02:30 【第一部】最近注目している機能 0:03:00 Claude Code Actions について 0:07:00 画像をドラックできるようになったこと 0:12:00 「Claude Code による AI 駆動開発入門」の出版裏話 0:21:50 Oikon さんの Claude Code キャッチアップのテクニック...

---

### [[A2UI] AI エージェントと UI をつなぐプロトコル A2UI を試してみる](https://zenn.dev/soundtricker/articles/a0c46f366ef953)

![[A2UI] AIエージェントとUIをつなぐプロトコル A2UIを試してみる](https://res.cloudinary.com/zenn/image/upload/s--B30uEuRR--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%255BA2UI%255D%2520AI%25E3%2582%25A8%25E3%2583%25BC%25E3%2582%25B8%25E3%2582%25A7%25E3%2583%25B3%25E3%2583%2588%25E3%2581%25A8UI%25E3%2582%2592%25E3%2581%25A4%25E3%2581%25AA%25E3%2581%2590%25E3%2583%2597%25E3%2583%25AD%25E3%2583%2588%25E3%2582%25B3%25E3%2583%25AB%2520A2UI%25E3%2582%2592%25E8%25A9%25A6%25E3%2581%2597%25E3%2581%25A6%25E3%2581%25BF%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Keisuke%2520Oohashi%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2gzVXhkWXNLcWpLdFhESXlXRk50UHZyZUxmN2dXaFVsOWNBSVRHLVE9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [AI コーディング実践環境の構築方法【2025 年 12 月】](https://zenn.dev/mkj/articles/bf59c4c86d98a8)

![AIコーディング実践環境の構築方法【2025年12月】](https://res.cloudinary.com/zenn/image/upload/s--VTCTxHVx--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:AI%25E3%2582%25B3%25E3%2583%25BC%25E3%2583%2587%25E3%2582%25A3%25E3%2583%25B3%25E3%2582%25B0%25E5%25AE%259F%25E8%25B7%25B5%25E7%2592%25B0%25E5%25A2%2583%25E3%2581%25AE%25E6%25A7%258B%25E7%25AF%2589%25E6%2596%25B9%25E6%25B3%2595%25E3%2580%25902025%25E5%25B9%25B412%25E6%259C%2588%25E3%2580%2591%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:%25E3%2581%258B%25E3%2582%2589%25E3%2581%2582%25E3%2581%2592%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2U2NGM3ZTBkMzIuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/g_south_west%2Ch_34%2Cl_default:og-publication-pro-mark-xcosax%2Cw_34%2Cx_217%2Cy_158/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E6%259D%25BE%25E5%25B0%25BE%25E7%25A0%2594%25E7%25A9%25B6%25E6%2589%2580%25E3%2583%2586%25E3%2583%2583%25E3%2582%25AF%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_255%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2hDZEtvakJfZXdDTjNCV1Z0WXIteFNIZ0hmRjlXZmt3QzI5c0Y0aXYwPXMyNTAtYw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [X ユーザーの J さん: 「元 Meta のエンジニアが、AI 駆動開発時代は AI が苦手とする 4 つの領域に特化して人間が介入するべきと提唱。 ✅️Resourcing（リソース管理） メモリリソースや、クラウドコストなどの最適化。特にどのクラウドや API サービスのコストを下げるため、どういったサービスをどう組み合わせるか？」 / X](https://x.com/j_kun_ml/status/2007946391545684269)

![XユーザーのJさん: 「元Metaのエンジニアが、AI駆動開発時代はAIが苦手とする4つの領域に特化して人間が介入するべきと提唱。  ✅️Resourcing（リソース管理） メモリリソースや、クラウドコストなどの最適化。特にどのクラウドやAPIサービスのコストを下げるため、どういったサービスをどう組み合わせるか？」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

### [実務で使い倒したので cc-sdd の仕様駆動開発プロセスを丁寧に解説してみた](https://zenn.dev/tmasuyama1114/articles/cc_sdd_whole_flow)

![実務で使い倒したので cc-sdd の仕様駆動開発プロセスを丁寧に解説してみた](https://res.cloudinary.com/zenn/image/upload/s--1lU0xtHb--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E5%25AE%259F%25E5%258B%2599%25E3%2581%25A7%25E4%25BD%25BF%25E3%2581%2584%25E5%2580%2592%25E3%2581%2597%25E3%2581%259F%25E3%2581%25AE%25E3%2581%25A7%2520cc-sdd%2520%25E3%2581%25AE%25E4%25BB%2595%25E6%25A7%2598%25E9%25A7%2586%25E5%258B%2595%25E9%2596%258B%25E7%2599%25BA%25E3%2583%2597%25E3%2583%25AD%25E3%2582%25BB%25E3%2582%25B9%25E3%2582%2592%25E4%25B8%2581%25E5%25AF%25A7%25E3%2581%25AB%25E8%25A7%25A3%25E8%25AA%25AC%25E3%2581%2597%25E3%2581%25A6%25E3%2581%25BF%25E3%2581%259F%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%25A8%25E3%2581%25BE%25E3%2581%25A0%2540AI%2520%25E9%25A7%2586%25E5%258B%2595%25E9%2596%258B%25E7%2599%25BA%25E6%2595%2599%25E8%2582%25B2%25E8%2580%2585%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzYyNTkxYzBkNDYuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

## Skills/MCP

### [Agent Skills 元年なのでオープンスタンダードになった Agent Skills について調べて使ってみた | DevelopersIO](https://dev.classmethod.jp/articles/agent-skills-2025-standardized-overview/)

![Agent Skills 元年なのでオープンスタンダードになった Agent Skills について調べて使ってみた | DevelopersIO](https://images.ctfassets.net/ct0aopd36mqt/3KBTm8tdpO9RJJuaVvVzod/a9964bb03097b448b2327edc6920bf9f/Claude.png)

世はまさに大 Agent Skills 時代なので、Agent Skills について調べて使ってみました。今度は作ってみます。

---

### [Agent Skills って何？ Anthropic の公式サンプル 16 個をすべて試してみた | DevelopersIO](https://dev.classmethod.jp/articles/try-agent-skills-anthropic-samples/)

![Agent Skills って何？ Anthropic の公式サンプル 16 個をすべて試してみた | DevelopersIO](https://images.ctfassets.net/ct0aopd36mqt/wp-thumbnail-75c24212db08a605cf51b1578f9a040c/f14b12b1b1cf9b5ed2427490ff86734d/eyecatch_anthropic)

最近話題の Agent Skills を理解するために Anthropic が提供するサンプルスキルを一通り試してみました

---

### [Claude Skills とは？ AI エージェント開発における新たなベストプラクティスをやさしく解説](https://codezine.jp/article/detail/22677)

![Claude Skillsとは？ AIエージェント開発における新たなベストプラクティスをやさしく解説](https://codezine.jp/static/images/article/22677/claudeskillsog.png)

2025 年 10 月 16 日、Anthropic 社が Claude Skills を公開し、IT エンジニア界隈で大きな話題となりました。本記事では Claude Skills の基本的な概念、それによって解決される課題、利用方法を解説します。大規模言語モデルの性能向上により、AI は知識レベルではすでにプロの研究者に匹敵するようになりましたが、特定分野のドメイン知識や作業手順といったコンテキストに依然として依存しています。Claude Skills を使用することで、より専門性の高い AI エージェントを構築でき、本当の意味での属人化を回避する銀の弾丸となり得ます。

---

### [Claude Code の Agent Skills は設定したほうがいい - じゃあ、おうちで学べる](https://syu-m-5151.hatenablog.com/entry/2025/12/19/173309)

![Claude Codeの Agent Skills は設定したほうがいい - じゃあ、おうちで学べる](https://ogimage.blog.st-hatena.com/8454420450094081900/17179246901334466532/1766305272)

Claude Code を使い始めて、様々な発信をしてきました。今回は「Agent Skills」について。これも設定しておくと、Claude Code がグッと使いやすくなる機能です。 Claude Code の settings.json は設定した方がいい - じゃあ、おうちで学べる Claude Code の CLAUDE.md は設定した方がいい - じゃあ、おうちで学べる Claude Code の .claude/commands/\*\*.md は設定した方がいい - じゃあ、おうちで学べる Claude Code の Hooks は設定したほうがいい - じゃあ、おうちで学べる Claude…

---

### [Anthropic Skills から AI プロダクト開発者が学べること：Skills は"業務マニュアル付きの道具箱"](https://zenn.dev/r_kaga/articles/810cc2e8326ca5)

![Anthropic SkillsからAIプロダクト開発者が学べること：Skillsは"業務マニュアル付きの道具箱"](https://res.cloudinary.com/zenn/image/upload/s--11lHW8q3--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Anthropic%2520Skills%25E3%2581%258B%25E3%2582%2589AI%25E3%2583%2597%25E3%2583%25AD%25E3%2583%2580%25E3%2582%25AF%25E3%2583%2588%25E9%2596%258B%25E7%2599%25BA%25E8%2580%2585%25E3%2581%258C%25E5%25AD%25A6%25E3%2581%25B9%25E3%2582%258B%25E3%2581%2593%25E3%2581%25A8%25EF%25BC%259ASkills%25E3%2581%25AF%2522%25E6%25A5%25AD%25E5%258B%2599%25E3%2583%259E%25E3%2583%258B%25E3%2583%25A5%25E3%2582%25A2%25E3%2583%25AB%25E4%25BB%2598%25E3%2581%258D%25E3%2581%25AE%25E9%2581%2593%25E5%2585%25B7%25E7%25AE%25B1%2522%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:r.kagaya%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2FlZTNjYzY3MDYuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

### [Agent Skills がハーネスの垣根を超える日](https://speakerdeck.com/gotalab555/agent-skillsgahanesunoyuan-gen-wochao-eruri)

![Agent Skillsがハーネスの垣根を超える日](https://files.speakerdeck.com/presentations/5c166c794af446a0a12e0830231b6133/slide_0.jpg?37824534)

2025 年 12 月 18 日、Anthropic が「Agent Skills」をオープン標準として公開し、OpenAI Codex や GitHub Copilot Agent なども続々と対応を表明しました。これは単なる機能追加ではなく、エージェント開発における「スキル共有革命」の始まりです。本スライドでは、「ど&hellip;

---

### [Agent Skills を一番かんたんに作る方法（Claude Code + skill-creator）](https://zenn.dev/aun_phonogram/articles/475f3cca8f40a3)

![Agent Skillsを一番かんたんに作る方法（Claude Code + skill-creator）](https://res.cloudinary.com/zenn/image/upload/s--HHABAkg7--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Agent%2520Skills%25E3%2582%2592%25E4%25B8%2580%25E7%2595%25AA%25E3%2581%258B%25E3%2582%2593%25E3%2581%259F%25E3%2582%2593%25E3%2581%25AB%25E4%25BD%259C%25E3%2582%258B%25E6%2596%25B9%25E6%25B3%2595%25EF%25BC%2588Claude%2520Code%2520%252B%2520skill-creator%25EF%25BC%2589%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:%25E5%2590%2589%25E5%25B2%25A1%25E8%25A3%2595%25E8%25B2%25B4%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzUwM2RkNmMyMzkuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:AUN%2520Tech%2520Blog%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzFmNzI5YzVhODEuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png?_a=BACAGSGT)

---

## AI エージェント

### [Ambient Agent とは？置き換わりうる業務と技術的なキーファクター｜ Seiji Takahashi@ベースマキナ](https://note.com/timakin/n/n5579d01bb3bb?sub_rt=share_pw)

![Ambient Agentとは？置き換わりうる業務と技術的なキーファクター｜Seiji Takahashi@ベースマキナ](https://assets.st-note.com/production/uploads/images/241811528/rectangle_large_type_2_e6c2450d9ca54ca24a342d71c9c7a40a.png?fit=bounds&quality=85&width=1280)

皆さまこんにちは、株式会社ベースマキナの代表取締役社長を務めております高橋（@**timakin**）です。 2025 年後半あたりから、「長時間タスクを実行できるエージェント」についての議論が増えてきたように感じます。周辺技術が出揃ってきた中で、たまに目にするようになったキーワードが「Ambient Agent」です。この記事では、Ambient Agent とは何か、どの業務が置き換わりうるのか、技術的なキーファクターについて整理してみます。 Ambient Agent とは Ambient Agent は、バックグラウンドで常時稼働し、イベントストリームを監視して適切なタイミング

---

### [LangChain: Chatbot を超える Ambient Agent とは？ - Qiita](https://qiita.com/RepKuririn/items/6650d7ff02f28de05133)

![LangChain: Chatbot を超えるAmbient Agent とは？ - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Farticle-ogp-background-afbab5eb44e0b055cce1258705637a91.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnFpaXRhLWltYWdlLXN0b3JlLnMzLmFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkYwJTJGMjE0MDEzJTJGcHJvZmlsZS1pbWFnZXMlMkYxNzUzNjg1MzE1P2l4bGliPXJiLTQuMC4wJmFyPTElM0ExJmZpdD1jcm9wJm1hc2s9ZWxsaXBzZSZiZz1GRkZGRkYmZm09cG5nMzImcz01ZDQ4ZmVmNmRkZGQ1YWFmNGRlMjViOTdiNjQwNjBjOQ%26blend-x%3D120%26blend-y%3D467%26blend-w%3D82%26blend-h%3D82%26blend-mode%3Dnormal%26s%3Db1fab81ab8536a48fb2925d958e05a62?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9TGFuZ0NoYWluJTNBJTIwQ2hhdGJvdCUyMCVFMyU4MiU5MiVFOCVCNiU4NSVFMyU4MSU4OCVFMyU4MiU4QkFtYmllbnQlMjBBZ2VudCUyMCVFMyU4MSVBOCVFMyU4MSVBRiVFRiVCQyU5RiZ0eHQtYWxpZ249bGVmdCUyQ3RvcCZ0eHQtY29sb3I9JTIzMUUyMTIxJnR4dC1mb250PUhpcmFnaW5vJTIwU2FucyUyMFc2JnR4dC1zaXplPTU2JnR4dC1wYWQ9MCZzPTJmM2Q4ODA4MGQ0YjZmYTk2Nzg0MWM5M2I5NjgxODYw&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDBSZXBLdXJpcmluJnR4dC1jb2xvcj0lMjMxRTIxMjEmdHh0LWZvbnQ9SGlyYWdpbm8lMjBTYW5zJTIwVzYmdHh0LXNpemU9MzYmdHh0LXBhZD0wJnM9NjVlYjRmNzc0NDQzZWIzY2M2MGU5NTBhNTE2MmQ3NTA&blend-x=242&blend-y=480&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&s=3b9822c3d6a12b54c9ad531d9d4adff1)

Ambient Agents and the New Agent Inbox ft. Harrison Chase https://www.youtube.com/watch?v=egSh4TxS5go 目次 はじめに：アンビエントエージェントとは チャットエージェン...

---

## ロボティクス

## その他 AI 利用 TIPS

### [Gemini 2.5 TTS のプロンプトガイド｜ npaka](https://note.com/npaka/n/n5402bf2851d0?sub_rt=share_sb)

![Gemini 2.5 TTS のプロンプトガイド｜npaka](https://assets.st-note.com/production/uploads/images/236174862/rectangle_large_type_2_40b97753575476530dfaa5f9686ec6d3.png?fit=bounds&quality=85&width=1280)

「Gemini 2.5 TTS」のプロンプトガイドをまとめました。 ・Speach generation - Prompting guide 1. Gemini 2.5 TTS のプロンプトガイド 「Gemini 2.5 TTS」 は、「何を話すか」だけでなく「どういう話し方で話すか」まで理解できる TTS です。ユーザーは監督のように、声の演技を細かく指定できます。 プロンプトを作るときは、次の 3 点を意識すると良いです。 ・どんなキャラクターか&nbsp;(性格・立場・声のイメージ) ・どんな場面か&nbsp;(場所・状況・感情の雰囲気) ・どう演じるか&nbsp;(話

---

### [Nano Banana Pro で ストーリー漫画の作成を試す｜ npaka](https://note.com/npaka/n/n5e7f167c9bf8?sub_rt=share_sb)

![Nano Banana Pro で ストーリー漫画の作成を試す｜npaka](https://assets.st-note.com/production/uploads/images/237800985/rectangle_large_type_2_bfca25d334fca61aab00b882599f9152.jpeg?fit=bounds&quality=85&width=1280)

「Nano Banana Pro」で ストーリー漫画の作成を試してみました。 1. Nano Banana Pro で ストーリー漫画の作成を試す 作成した漫画は、次のとおりです。

---

### [Nano Banana Pro で 1 ページ漫画ができるまで｜ npaka](https://note.com/npaka/n/n19d440a7b100)

![Nano Banana Pro で1ページ漫画ができるまで｜npaka](https://assets.st-note.com/production/uploads/images/238783079/rectangle_large_type_2_56a62e741fc39b0d68098903ffb8bbcd.jpeg?fit=bounds&quality=85&width=1280)

「Nano Banana Pro」で 1 ページ漫画ができるまで (現状版) をまとめました。生成回数は 13 回、作業時間は 30 分ほどになります。 1. Nano Banana Pro で 1 ページ漫画の作成 作成した 1 ページ漫画は、次のとおりです。 2. Nano Banana Pro で 1 ページ漫画ができるまで 2-1. ベースの作成 はじめに、ベースとなる漫画を作成します。1K で作成しています。 「Google AI Studio」を使ってます。 ・参照画像 ・プロンプト # 指示
日本の AI 紹介漫画を描いてください。
右から左読み進める日本漫画のフォーマット (Ori

---

### [X ユーザーの AIDB さん: 「Google の研究者らが短い論文で「LLM に質問するとき、同じ質問を 2 回続けて入力するだけで、LLM の回答精度が上がる」という発見を報告しています。 あまりに単純すぎて見落とされていた改善策が、主要なモデルすべてで一貫して効果を発揮したという点が、この研究の意外性です。 なぜこれが効くのか。 https://t.co/gwarLLw0AY」 / X](https://x.com/ai_database/status/2004784054240247996)

![XユーザーのAIDBさん: 「Googleの研究者らが短い論文で「LLMに質問するとき、同じ質問を2回続けて入力するだけで、LLMの回答精度が上がる」という発見を報告しています。 あまりに単純すぎて見落とされていた改善策が、主要なモデルすべてで一貫して効果を発揮したという点が、この研究の意外性です。  なぜこれが効くのか。 https://t.co/gwarLLw0AY」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---

## 気になるツール/サービス 1(開発/情報系)

## 気になるツール/サービス 2(画像/動画/3D/音声/音楽生成、認識技術、XR/ゲーム関連等)

### [エンジニアの「絵で説明して」問題、Nano Banana Pro（Gemini 3 Pro Image）でどこまで解消できるか試してみた - Qiita](https://qiita.com/ntaka329/items/6609861b7149c2ee8331)

![エンジニアの「絵で説明して」問題、Nano Banana Pro（Gemini 3 Pro Image）でどこまで解消できるか試してみた - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Farticle-ogp-background-afbab5eb44e0b055cce1258705637a91.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1pbWFnZS1zdG9yZSUyRjAlMkY0MTc0MTgwJTJGZDcwMzlhMTI3M2Q5ZDhmZjljOTE3NTI1Y2Q5ZDk1NDlmM2MxOWJkMiUyRnhfbGFyZ2UucG5nJTNGMTc1NjI3NDgwOT9peGxpYj1yYi00LjAuMCZhcj0xJTNBMSZmaXQ9Y3JvcCZtYXNrPWVsbGlwc2UmYmc9RkZGRkZGJmZtPXBuZzMyJnM9Mzk5ZjczZWNiYTc5ZGJmZWUwYjJiYWRiN2FjOGQxMTQ%26blend-x%3D120%26blend-y%3D462%26blend-w%3D90%26blend-h%3D90%26blend-mode%3Dnormal%26mark64%3DaHR0cHM6Ly9xaWl0YS1vcmdhbml6YXRpb24taW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1vcmdhbml6YXRpb24taW1hZ2UlMkZlYmQ5Njg3Yjk0MzAwMWI5NzlkNmU0YWY1MGFiYWU4YTc5MWE4ZGE1JTJGb3JpZ2luYWwuanBnJTNGMTc1NjE4NjM1Mz9peGxpYj1yYi00LjAuMCZ3PTQ0Jmg9NDQmZml0PWNyb3AmbWFzaz1jb3JuZXJzJmNvcm5lci1yYWRpdXM9OCZiZz1GRkZGRkYmYm9yZGVyPTIlMkNGRkZGRkYmZm09cG5nMzImcz01MTU4NTU3MDhiYjU3YTNkNjYxZGZmZWQ4YmZkMWNiNQ%26mark-x%3D186%26mark-y%3D515%26mark-w%3D40%26mark-h%3D40%26s%3D04b2575760599b7aed5755edc47b452a?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9JUUzJTgyJUE4JUUzJTgzJUIzJUUzJTgyJUI4JUUzJTgzJThCJUUzJTgyJUEyJUUzJTgxJUFFJUUzJTgwJThDJUU3JUI1JUI1JUUzJTgxJUE3JUU4JUFBJUFDJUU2JTk4JThFJUUzJTgxJTk3JUUzJTgxJUE2JUUzJTgwJThEJUU1JTk1JThGJUU5JUExJThDJUUzJTgwJTgxTmFubyUyMEJhbmFuYSUyMFBybyVFRiVCQyU4OEdlbWluaSUyMDMlMjBQcm8lMjBJbWFnZSVFRiVCQyU4OSVFMyU4MSVBNyVFMyU4MSVBOSVFMyU4MSU5MyVFMyU4MSVCRSVFMyU4MSVBNyVFOCVBNyVBMyVFNiVCNiU4OCVFMyU4MSVBNyVFMyU4MSU4RCVFMyU4MiU4QiVFMiU4MCVBNiZ0eHQtYWxpZ249bGVmdCUyQ3RvcCZ0eHQtY29sb3I9JTIzMUUyMTIxJnR4dC1mb250PUhpcmFnaW5vJTIwU2FucyUyMFc2JnR4dC1zaXplPTU2JnR4dC1wYWQ9MCZzPThkYWYyNDZhYTYwYzVmYzg1NDI5NWI2Yjg4MDVjZjU3&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDBudGFrYTMyOSZ0eHQtY29sb3I9JTIzMUUyMTIxJnR4dC1mb250PUhpcmFnaW5vJTIwU2FucyUyMFc2JnR4dC1zaXplPTM2JnR4dC1wYWQ9MCZzPWMyMjY1MWI5MTUzMzZlYWQ4YTlhZjc3NzY3YWM4NTY4&blend-x=242&blend-y=454&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&txt64=R01P44Kz44ON44Kv44OI5qCq5byP5Lya56S-&txt-x=242&txt-y=539&txt-width=838&txt-clip=end%2Cellipsis&txt-color=%231E2121&txt-font=Hiragino%20Sans%20W6&txt-size=28&s=9982306c77177d13ab2ea6a29e62fc25)

はじめに GMO コネクトの永田です。 エンジニアやアーキテクトの皆さん、こんな経験はありませんか？ 「この技術的な内容、文字だけじゃ分かりにくいから絵で説明して」 分かりやすく説明したい気持ちはあるものの、AWS 構成図やアーキテクチャ図を作るのは正直かなり面倒。構成を整理...

---

## その他

### [X ユーザーのフルスイング by DeNA さん: 「【DeNA 社員の AI 活用 100 本まとめスライド公開！📢】 🔗https://t.co/0DtSwfxGSh 「現場の AI 活用事例」を全 100P！のスライドにまとめて一挙公開しました 👀 https://t.co/SKiAlx2wXk」 / X](https://x.com/DeNA_fullswing/status/2003269327966097679)

![Xユーザーのフルスイング by DeNAさん: 「【DeNA社員のAI活用100本まとめスライド公開！📢】  🔗https://t.co/0DtSwfxGSh  「現場のAI活用事例」を全100P！のスライドにまとめて一挙公開しました👀 https://t.co/SKiAlx2wXk」 / X](https://abs.twimg.com/rweb/ssr/default/v2/og/image.png)

---
