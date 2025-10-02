# このページについて

- 2025/07/09 から 2025/08/07 の期間で、個人的に気になった AI ニュース/記事/ポストなどまとめたページです。
- TechFirst Leaders の社内 AI 勉強会用に整理したものを公開しています。
- Web 開発/システム開発エンジニア寄りの視点でまとめています。
- まとめた人：[@mouri45](https://x.com/mouri45)

# 気になるトピック

- Amazon から AI コーディングエディタの Kiro がリリースされ、仕様駆動開発が注目されました。その流れを受け、Claude Code で仕様駆動開発を行う取り組みをしている人が AI コーディング界隈で多くみられました。
- Claude Code にサブエージェントやコンテナの機能が追加されました。
- OpenAI の gpt-oss や Alibaba の Qwen-Coder などオープンなモデルがリリースされローカルでの LLM 利用が注目を集めました。
- その他個人的に、コンフリクトを許容する AI コーディングと相性のいいソースコードバージョン管理システムの Jujutsu とプロジェクトを意味的に理解して AI コーディングエージェントを効率化する Serena MCP が気になりました。

# カテゴリ

**AI 企業/LLM 関連ニュース**：[OpenAI](#openai) | [Google](#google) | [Anthropic](#anthropic) | [MS/GitHub](#msgithub) | [Amazon](#amazon) | [ローカル LLM](#ローカル-llm) | [その他 LLM 関連](#その他-llm-関連)

**注目トピック**：[AI コーディング/AI 駆動開発](#ai-コーディングai-駆動開発) | [MCP](#mcp) | [AI エージェント](#ai-エージェント) | [ローカル LLM](#ローカル-llm) | [ロボティクス](#ロボティクス)

**ツール/サービス**：[開発/情報系](#気になるツールサービス-1開発情報系) | [画像/動画/3D 等](#気になるツールサービス-2画像動画3d音声音楽生成認識技術xrゲーム関連等) | [その他](#その他)

# AI 企業/LLM 関連ニュース

## OpenAI

### [OpenAI がオープンウェイトの AI 推論モデル「gpt-oss」を発表、軽量版はノート PC やスマートフォンでも動作可能](https://gigazine.net/news/20250806-openai-gpt-oss/)

![OpenAIがオープンウェイトのAI推論モデル「gpt-oss」を発表、軽量版はノートPCやスマートフォンでも動作可能](https://i.gzn.jp/img/2025/08/06/openai-gpt-oss/00_m.jpg)

OpenAI が、ノート PC でも動作可能な無料のオープンウェイトモデル「gpt-oss」を公開したと 2025 年 8 月 5 日に発表しました。このモデルは OpenAI にとって、2019 年に公開された GPT-2 以来のオープンウェイト言語モデルとなります。

---

### [ChatGPT agent の発表まとめ](https://zenn.dev/schroneko/articles/introducing-chatgpt-agent)

![ChatGPT agent の発表まとめ](https://res.cloudinary.com/zenn/image/upload/s--S8p53D5J--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:ChatGPT%2520agent%2520%25E3%2581%25AE%25E7%2599%25BA%25E8%25A1%25A8%25E3%2581%25BE%25E3%2581%25A8%25E3%2582%2581%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%25AC%25E3%2581%2593%25E3%2581%25AC%25E3%2581%2593%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzE4ZDE4NWExYTYuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [OpenAI の「ChatGPT Agent」徹底解説：タスクを自律的にこなす次世代 AI エージェントの正体 - Qiita](https://qiita.com/softbase/items/dbe0787cb94fae717dcb)

![OpenAIの「ChatGPT Agent」徹底解説：タスクを自律的にこなす次世代AIエージェントの正体 - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Farticle-ogp-background-afbab5eb44e0b055cce1258705637a91.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1pbWFnZS1zdG9yZSUyRjAlMkYxMjU3NDYlMkYxM2Q3NGUwNzkzZWNiZDU1NjYwNGIzZTBmMDM1Y2RhY2VhN2MyOWRiJTJGbGFyZ2UucG5nJTNGMTc0NjE5MjIyNj9peGxpYj1yYi00LjAuMCZhcj0xJTNBMSZmaXQ9Y3JvcCZtYXNrPWVsbGlwc2UmYmc9RkZGRkZGJmZtPXBuZzMyJnM9ZmM2ODc3MjMxNjNlMDM2ZjExMTM3NzIxMDdjNzA1OWY%26blend-x%3D120%26blend-y%3D467%26blend-w%3D82%26blend-h%3D82%26blend-mode%3Dnormal%26s%3D237669052e2f7e660e5a5561ea324508?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9T3BlbkFJJUUzJTgxJUFFJUUzJTgwJThDQ2hhdEdQVCUyMEFnZW50JUUzJTgwJThEJUU1JUJFJUI5JUU1JUJBJTk1JUU4JUE3JUEzJUU4JUFBJUFDJUVGJUJDJTlBJUUzJTgyJUJGJUUzJTgyJUI5JUUzJTgyJUFGJUUzJTgyJTkyJUU4JTg3JUFBJUU1JUJFJThCJUU3JTlBJTg0JUUzJTgxJUFCJUUzJTgxJTkzJUUzJTgxJUFBJUUzJTgxJTk5JUU2JUFDJUExJUU0JUI4JTk2JUU0JUJCJUEzQUklRTMlODIlQTglRTMlODMlQkMlRTMlODIlQjglRTMlODIlQTclRTMlODMlQjMlRTMlODMlODglRTMlODElQUUlRTYlQUQlQTMlRTQlQkQlOTMmdHh0LWFsaWduPWxlZnQlMkN0b3AmdHh0LWNvbG9yPSUyMzFFMjEyMSZ0eHQtZm9udD1IaXJhZ2lubyUyMFNhbnMlMjBXNiZ0eHQtc2l6ZT01NiZ0eHQtcGFkPTAmcz0xZmI0NzMyNTk1MTRiYTQwZjE3MGM5MWE2M2ViYzg3NA&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDBzb2Z0YmFzZSZ0eHQtY29sb3I9JTIzMUUyMTIxJnR4dC1mb250PUhpcmFnaW5vJTIwU2FucyUyMFc2JnR4dC1zaXplPTM2JnR4dC1wYWQ9MCZzPTZjN2ExOTkxNmJiMWZjNzExZGIxNjFjYTA0MmVjNmFh&blend-x=242&blend-y=480&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&s=4e4db08794109a1d50e16601e9e4f661)

OpenAI の「ChatGPT Agent」徹底解説：タスクを自律的にこなす次世代 AI エージェントの正体 2025 年 7 月、OpenAI がまたしても革命を起こしました。新たに発表された 「ChatGPT Agent」 は、従来のチャットボットとは一線を画す存在。自然言語で指...

---

### [学習モードが登場](https://openai.com/ja-JP/index/chatgpt-study-mode/)

![学習モードが登場](https://images.ctfassets.net/kftzwdyauwt9/7MX2mPI1TJGJqIdwZpRcnY/c54d6250b7ef8cccf09724330fb3d200/Blog_StudyMode_OpenGraph.png?w=1600&h=900&fit=fill)

すぐに回答を示すのではなく、段階的に考えながら理解を深められるよう学習をサポートします。

---

### [OpenAI API による 高い入力忠実度での画像生成を試す｜ npaka](https://note.com/npaka/n/ne83ca0fd20d3)

![OpenAI API による 高い入力忠実度での画像生成を試す｜npaka](https://assets.st-note.com/production/uploads/images/202675886/rectangle_large_type_2_9e9ed22448161802f663ebac5e59538d.png?fit=bounds&quality=85&width=1280)

以下の記事が面白かったので、簡単にまとめました。 ・Generate images with high input fidelity 1. はじめに この記事では、「Image API」と「Responses」の画像生成ツールで利用可能な「input_fidelity」パラメータを活用して、入力の特徴を保持する方法を説明します。input_fidelity="high" に設定すると、顔やロゴなど、出力に高い忠実度が求められる細部を含む画像を編集する場合に特に便利です。 「OpenAI API」を使用した画像生成にまだ慣れていない場合は、入門用画像生成 Cookbook から

---

### [X ユーザーの Maki@Sunwood AI Labs.さん: 「GPT Image Input fidelity で 1 枚の画像から表情を変えてみた！！！ これエグイな！！！！ https://t.co/fRisREqPcy」 / X](https://x.com/hAru_mAki_ch/status/1945839487101366535)

![XユーザーのMaki@Sunwood AI Labs.さん: 「GPT Image Input fidelity で1枚の画像から表情を変えてみた！！！ これエグイな！！！！ https://t.co/fRisREqPcy」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

## Google

### [Gemini アプリに 10 ページの絵本生成 Gems「Storybook」追加　無料版、日本語でも](https://www.itmedia.co.jp/news/articles/2508/06/news069.html)

![Geminiアプリに10ページの絵本生成Gems「Storybook」追加　無料版、日本語でも](https://image.itmedia.co.jp/news/articles/2508/06/cover_news069.jpg)

Google は、Gemini アプリ上で AI が 10 ページの絵本を生成する新機能「Storybook」を発表した。プロンプトや写真、文書から物語とイラスト、ナレーションを自動作成する。日本語にも対応し、無料プランでも利用可能だ。

---

### [Google DeepMind、リアルタイムで世界を生成する AI「Genie 3」発表　“AGI への足がかり”](https://www.itmedia.co.jp/aiplus/articles/2508/06/news065.html)

![Google DeepMind、リアルタイムで世界を生成するAI「Genie 3」発表　“AGIへの足がかり”](https://image.itmedia.co.jp/aiplus/articles/2508/06/cover_news065.jpg)

Google DeepMind は、プロンプトから対話可能な世界をリアルタイムで生成する AI「Genie 3」を発表した。物体の状態を記憶する「ワールドメモリ」機能を搭載し、数分間の一貫性を維持する。AGI への足がかりと位置づけられ、AI エージェントの訓練などに活用される。

---

### [Google、マルチエージェント AI「Deep Think」提供開始　「AI Ultra」プランで](https://www.itmedia.co.jp/aiplus/articles/2508/02/news026.html)

![Google、マルチエージェントAI「Deep Think」提供開始　「AI Ultra」プランで](https://image.itmedia.co.jp/aiplus/articles/2508/02/cover_news026.jpg)

Google は、高度な問題解決 AI「Deep Think」の提供を開始した。「Gemini 2.5 Pro」のマルチエージェント機能で、並列思考により複雑な問題の最適解を導く。国際数学オリンピックで金メダル級の性能を示したモデルの派生版で、「Google AI Ultra」プラン限定で提供される。

---

### [Google による Deep Research の新手法、OpenAI 超え](https://zenn.dev/knowledgesense/articles/5a341158c2c9ab)

![Googleによる Deep Research の新手法、OpenAI超え](https://res.cloudinary.com/zenn/image/upload/s--WmOUiL4T--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Google%25E3%2581%25AB%25E3%2582%2588%25E3%2582%258B%2520Deep%2520Research%2520%25E3%2581%25AE%25E6%2596%25B0%25E6%2589%258B%25E6%25B3%2595%25E3%2580%2581OpenAI%25E8%25B6%2585%25E3%2581%2588%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Atsushi%2520Kadowaki%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly96ZW5uLmRldi9pbWFnZXMvZGVmYXVsdC1wdWJsaWNhdGlvbi1hdmF0YXIucG5n%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E3%2583%258A%25E3%2583%25AC%25E3%2583%2583%25E3%2582%25B8%25E3%2582%25BB%25E3%2583%25B3%25E3%2582%25B9%2520-%2520AI%25E7%259F%25A5%25E8%25A6%258B%25E5%2585%25B1%25E6%259C%2589%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzRlMjk5Y2IwN2IuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Google、AI を使って非構造化テキストから構造化データを抽出するオープンソース Python ライブラリ「LangExtract」をリリース | gihyo.jp](https://gihyo.jp/article/2025/08/langextract)

![Google、AIを使って非構造化テキストから構造化データを抽出するオープンソースPythonライブラリ「LangExtract」をリリース | gihyo.jp](https://gihyo.jp/assets/images/ICON/2025/2589_langextract.png)

Google は 2025 年 7 月 30 日、非構造化テキストから構造化データを抽出するオープンソースの Python ライブラリ「LangExtract」をリリースした。

---

### [Google、非同期コーディングエージェント「Jules」を一般公開 ～無償でも利用可能／「GitHub」と統合、「Gemini 2.5 Pro」で計画・解決](https://forest.watch.impress.co.jp/docs/news/2037539.html)

![Google、非同期コーディングエージェント「Jules」を一般公開 ～無償でも利用可能／「GitHub」と統合、「Gemini 2.5 Pro」で計画・解決](https://forest.watch.impress.co.jp/img/wf/list/2037/539/jules.png)

米 Google は 8 月 6 日（現地時間）、非同期コーディングエージェント「Jules」を一般公開した。これまでベータ版としてテストが続けられていたが、「Gemini 2.5」を搭載して正式に提供されることになった。

---

## Anthropic

### [Anthropic が「Claude Opus 4.1」をリリース、コーディング能力が向上](https://gigazine.net/news/20250806-anthropic-claude-opus-4-1/)

![Anthropicが「Claude Opus 4.1」をリリース、コーディング能力が向上](https://i.gzn.jp/img/2025/08/06/anthropic-claude-opus-4-1/00.png)

AI 企業の Anthropic が、推論能力やコーディング能力に優れた AI モデル「Claude Opus 4.1」をリリースしました。

---

### [Anthropic、「Claude Code」に自動セキュリティレビュー機能を導入](https://japan.zdnet.com/article/35236436/)

![Anthropic、「Claude Code」に自動セキュリティレビュー機能を導入](https://japan.zdnet.com/storage/2025/08/07/d73f9c3e33b8347c9f76e640c898ce36/anthropic-claude-code_1280.jpg)

Anthropic が「Claude Code」に新機能を実装した。セキュリティ上の問題を、より簡単に発見し修正できるセキュリティレビュー機能だ。

---

### [サブエージェント - Anthropic](https://docs.anthropic.com/ja/docs/claude-code/sub-agents)

![サブエージェント - Anthropic](https://anthropic.mintlify.app/_next/image?url=%2Fapi%2Fog%3Fdivision%3DDocumentation%26mode%3Dlight%26title%3D%25E3%2582%25B5%25E3%2583%2596%25E3%2582%25A8%25E3%2583%25BC%25E3%2582%25B8%25E3%2582%25A7%25E3%2583%25B3%25E3%2583%2588%26description%3DClaude%2BCode%25E3%2581%25A7%25E3%2582%25BF%25E3%2582%25B9%25E3%2582%25AF%25E5%259B%25BA%25E6%259C%2589%25E3%2581%25AE%25E3%2583%25AF%25E3%2583%25BC%25E3%2582%25AF%25E3%2583%2595%25E3%2583%25AD%25E3%2583%25BC%25E3%2581%25A8%25E6%2594%25B9%25E5%2596%2584%25E3%2581%2595%25E3%2582%258C%25E3%2581%259F%25E3%2582%25B3%25E3%2583%25B3%25E3%2583%2586%25E3%2582%25AD%25E3%2582%25B9%25E3%2583%2588%25E7%25AE%25A1%25E7%2590%2586%25E3%2581%25AE%25E3%2581%259F%25E3%2582%2581%25E3%2581%25AB%25E3%2580%2581%25E5%25B0%2582%25E9%2596%2580%25E5%258C%2596%25E3%2581%2595%25E3%2582%258C%25E3%2581%259FAI%25E3%2582%25B5%25E3%2583%2596%25E3%2582%25A8%25E3%2583%25BC%25E3%2582%25B8%25E3%2582%25A7%25E3%2583%25B3%25E3%2583%2588%25E3%2582%2592%25E4%25BD%259C%25E6%2588%2590%25E3%2583%25BB%25E4%25BD%25BF%25E7%2594%25A8%25E3%2581%2597%25E3%2581%25BE%25E3%2581%2599%25E3%2580%2582%26logoLight%3Dhttps%253A%252F%252Fmintlify.s3.us-west-1.amazonaws.com%252Fanthropic%252Flogo%252Flight.svg%26logoDark%3Dhttps%253A%252F%252Fmintlify.s3.us-west-1.amazonaws.com%252Fanthropic%252Flogo%252Fdark.svg%26primaryColor%3D%25230E0E0E%26lightColor%3D%2523D4A27F%26darkColor%3D%25230E0E0E&w=1200&q=100)

Claude Code でタスク固有のワークフローと改善されたコンテキスト管理のために、専門化された AI サブエージェントを作成・使用します。

---

### [Claude Code の公式 DevContainer について](https://zenn.dev/mixi/articles/c2a11b1765b149)

![Claude Codeの公式DevContainerについて](https://res.cloudinary.com/zenn/image/upload/s--UEv8oBb0--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AE%25E5%2585%25AC%25E5%25BC%258FDevContainer%25E3%2581%25AB%25E3%2581%25A4%25E3%2581%2584%25E3%2581%25A6%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:%25E3%2581%2597%25E3%2582%258D%25E3%2581%25A1%25E3%2582%2583%25E3%2582%2593%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2UzY2IwNWVmMTMuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/g_south_west%2Ch_34%2Cl_default:og-publication-pro-mark-xcosax%2Cw_34%2Cx_217%2Cy_158/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:MIXI%2520DEVELOPERS%2520Tech...%2Cx_255%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUNnOG9jSmdPdXkwaXpkYmFSWl90VWZQc2tlWWRFNWNiQjFZVzVSRDlyMk94QXNLcjAxd3IzSjI9czk2LWM=%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーのぬこぬこ | NUKO さん: 「Anthropic の公式学習教材 Anthropic Academy に 6 つの動画コースが追加 Anthropic API / Amazon Bedrock / Vertex AI を活用した Claude の解説から MCP や Claude Code の使い方まで 各ページ右上にある Open in Claude をクリックすると FAQ 形式で学ぶこともできて便利 https://t.co/SPFGSCy2SG https://t.co/9yGytAsHCf」 / X](https://x.com/schroneko/status/1942987150842286374)

![Xユーザーのぬこぬこ | NUKOさん: 「Anthropic の公式学習教材 Anthropic Academy に 6 つの動画コースが追加  Anthropic API / Amazon Bedrock / Vertex AI を活用した Claude の解説から MCP や Claude Code の使い方まで  各ページ右上にある Open in Claude をクリックすると FAQ 形式で学ぶこともできて便利 https://t.co/SPFGSCy2SG https://t.co/9yGytAsHCf」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

## MS/GitHub

### [GitHub、自然言語の指示だけでアプリが自動生成される「GitHub Spark」パブリックプレビュー開始](https://www.publickey1.jp/blog/25/githubgithub_spark_1.html)

![GitHub、自然言語の指示だけでアプリが自動生成される「GitHub Spark」パブリックプレビュー開始](https://www.publickey1.jp/2025/github-spark-pp01.png)

GitHub は、自然言語で指示するだけで生成 AI によって TypeScript と React を用いたフルスタックのアプリケーションが自動的に生成される「GitHub Spark」のパブリックプレビュー開始を発表しました。 Today we’re...

---

## Amazon

### [Kiro のご紹介 – プロトタイプからプロダクションまで、あなたと共に働く新しい Agentic IDE | Amazon Web Services](https://aws.amazon.com/jp/blogs/news/introducing-kiro/)

![Kiro のご紹介 – プロトタイプからプロダクションまで、あなたと共に働く新しい Agentic IDE | Amazon Web Services](https://d2908q01vomqb2.cloudfront.net/b3f0c7f6bb763af1be91d9e74eabfeb199dc1f1f/2025/07/14/emlUxRBb.jpeg)

コンセプトからプロダクションまで、AI エージェントとの作業を簡素化した開発者体験を通じて開発を支援する AI IDE（統合開発環境）、Kiro の発表を嬉しく思います。Kiro は Vibe Coding "も" 得意ですが、それをはるかに超えています。Kiro の強みは、スペック (spec) やフック (hook) などの機能を使って、これらのプロトタイプをプロダクションシステムに移行することです。

---

### [X ユーザーのみぃ 🌻 エンジニアさん: 「そういえば順番待たずに普通に brew で入れられたから使ってみる！ https://t.co/Z0GPSfm3mI」 / X](https://x.com/maso_mi9808/status/1947086392141693230)

![Xユーザーのみぃ🌻エンジニアさん: 「そういえば順番待たずに普通にbrewで入れられたから使ってみる！ https://t.co/Z0GPSfm3mI」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの Gota@Data Analyst さん: 「AWS ブログでサラッと Kiro の背景にある考え方「AI 駆動開発ライフサイクル (AI-DLC)」が公開されている！ 中にあるホワイトペーパーまで必読！ https://t.co/eYMQtdOnPg」 / X](https://x.com/gota_bara/status/1951338077403881544)

![XユーザーのGota@Data Analystさん: 「AWSブログでサラッとKiroの背景にある考え方「AI駆動開発ライフサイクル (AI-DLC)」が公開されている！  中にあるホワイトペーパーまで必読！ https://t.co/eYMQtdOnPg」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

## ローカル LLM

## その他 LLM 関連

### [Claude Sonnet 4 に匹敵するコーディング特化のオープンモデル「Qwen3-Coder」を Alibaba が発表](https://gigazine.net/news/20250723-alibaba-qwen3-coder/)

![Claude Sonnet 4に匹敵するコーディング特化のオープンモデル「Qwen3-Coder」をAlibabaが発表](https://i.gzn.jp/img/2025/07/23/alibaba-qwen3-coder/00.png)

Alibaba の大規模言語モデル「Qwen」の研究チームが、コーディングに特化したエージェントモデル「Qwen3-Coder」を発表しました。パラメータ数 4800 億・アクティブパラメータ数 350 億のモデル「Qwen3-Coder-480B-A35B-Instruct」は、Claude Sonnet 4 に匹敵する最先端の結果を達成しています。

---

### [Grok 4 の発表まとめ＆試してみた](https://zenn.dev/schroneko/articles/grok-4-overview-and-review)

![Grok 4 の発表まとめ＆試してみた](https://res.cloudinary.com/zenn/image/upload/s--Ocm5Txmn--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Grok%25204%2520%25E3%2581%25AE%25E7%2599%25BA%25E8%25A1%25A8%25E3%2581%25BE%25E3%2581%25A8%25E3%2582%2581%25EF%25BC%2586%25E8%25A9%25A6%25E3%2581%2597%25E3%2581%25A6%25E3%2581%25BF%25E3%2581%259F%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%25AC%25E3%2581%2593%25E3%2581%25AC%25E3%2581%2593%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzE4ZDE4NWExYTYuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Grok の AI 美少女「Ani」が巻き起こす AI コンパニオン革命、イーロンは最初からこれを狙っていた？ #エキスパートトピ（いしたにまさき） - エキスパート - Yahoo!ニュース](https://news.yahoo.co.jp/expert/articles/2d8f7a7a446f7c6f5f1922fb827f6fbe92e83704)

![GrokのAI美少女「Ani」が巻き起こすAIコンパニオン革命、イーロンは最初からこれを狙っていた？ #エキスパートトピ（いしたにまさき） - エキスパート - Yahoo!ニュース](https://newsatcl-pctr.c.yimg.jp/t/iwiz-yn/rpr/ishitanimasaki/02289804/title-1752569258096.jpeg?exp=10800)

イーロン・マスク率いる xAI が、AI チャットボット「Grok」に革新的な新機能「コンパニオンモード」を追加し、大きな話題となっている。特に注目を集めているのが、黒いゴスドレスを着た金髪ツインテールの美

---

# 注目トピック

## AI コーディング/AI 駆動開発

### [Kiro から考える AI コーディングツールの潮流](https://speakerdeck.com/s4yuba/kirokarakao-eru-aikodeinguturunochao-liu)

![Kiroから考える AIコーディングツールの潮流](https://files.speakerdeck.com/presentations/210e8f4afa5946e89d052fb69de5a7f4/slide_0.jpg?36096988)

RevenueCat 主催 Vibe Coding Catfe（バイブコーディングカフェ）の登壇資料です

English Ver: https://speakerdeck.com/s4yuba/ai-coding-tool-trends-lessons-from-kiro

Event link&hellip;

---

### [amazon の出した IDE「kiro」がめちゃくちゃ未来だったので Claude Code ユーザーの人はみんな一度試してみてほしい](https://zenn.dev/sesere/articles/31d4b460c949e5)

![amazonの出したIDE「kiro」がめちゃくちゃ未来だったのでClaude Codeユーザーの人はみんな一度試してみてほしい](https://res.cloudinary.com/zenn/image/upload/s--8U9a1--s--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:amazon%25E3%2581%25AE%25E5%2587%25BA%25E3%2581%2597%25E3%2581%259FIDE%25E3%2580%258Ckiro%25E3%2580%258D%25E3%2581%258C%25E3%2582%2581%25E3%2581%25A1%25E3%2582%2583%25E3%2581%258F%25E3%2581%25A1%25E3%2582%2583%25E6%259C%25AA%25E6%259D%25A5%25E3%2581%25A0%25E3%2581%25A3%25E3%2581%259F%25E3%2581%25AE%25E3%2581%25A7Claude%2520Code%25E3%2583%25A6%25E3%2583%25BC%25E3%2582%25B6%25E3%2583%25BC%25E3%2581%25AE%25E4%25BA%25BA%25E3%2581%25AF%25E3%2581%25BF%25E3%2582%2593%25E3%2581%25AA%25E4%25B8%2580%25E5%25BA%25A6%25E8%25A9%25A6...%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:sesere%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzg4NjY3ZDcwMjMuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Kiro の Agent Steering の仕組みが良いと思った話](https://zenn.dev/oikon/articles/kiro-steering)

![KiroのAgent Steeringの仕組みが良いと思った話](https://res.cloudinary.com/zenn/image/upload/s--AIL2eek---/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Kiro%25E3%2581%25AEAgent%2520Steering%25E3%2581%25AE%25E4%25BB%2595%25E7%25B5%2584%25E3%2581%25BF%25E3%2581%258C%25E8%2589%25AF%25E3%2581%2584%25E3%2581%25A8%25E6%2580%259D%25E3%2581%25A3%25E3%2581%259F%25E8%25A9%25B1%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Oikon%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzFlNjI2MjNlZTQuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Kiro の仕様書駆動開発プロセスを Claude Code で徹底的に再現した](https://zenn.dev/gotalab/articles/3db0621ce3d6d2)

![Kiroの仕様書駆動開発プロセスをClaude Codeで徹底的に再現した](https://res.cloudinary.com/zenn/image/upload/s--gkBXU69n--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Kiro%25E3%2581%25AE%25E4%25BB%2595%25E6%25A7%2598%25E6%259B%25B8%25E9%25A7%2586%25E5%258B%2595%25E9%2596%258B%25E7%2599%25BA%25E3%2583%2597%25E3%2583%25AD%25E3%2582%25BB%25E3%2582%25B9%25E3%2582%2592Claude%2520Code%25E3%2581%25A7%25E5%25BE%25B9%25E5%25BA%2595%25E7%259A%2584%25E3%2581%25AB%25E5%2586%258D%25E7%258F%25BE%25E3%2581%2597%25E3%2581%259F%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Gota%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzE3OGM0MmRlZjIuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Kiro と Claude Code の組み合わせで開発の質と速度を両取りできた](https://zenn.dev/ubie_dev/articles/kiro-claude-code)

![KiroとClaude Codeの組み合わせで開発の質と速度を両取りできた](https://res.cloudinary.com/zenn/image/upload/s--xpAYwKRm--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Kiro%25E3%2581%25A8Claude%2520Code%25E3%2581%25AE%25E7%25B5%2584%25E3%2581%25BF%25E5%2590%2588%25E3%2582%258F%25E3%2581%259B%25E3%2581%25A7%25E9%2596%258B%25E7%2599%25BA%25E3%2581%25AE%25E8%25B3%25AA%25E3%2581%25A8%25E9%2580%259F%25E5%25BA%25A6%25E3%2582%2592%25E4%25B8%25A1%25E5%258F%2596%25E3%2582%258A%25E3%2581%25A7%25E3%2581%258D%25E3%2581%259F%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:%25E9%25B9%25BF%25E9%2587%258E%2520%25E5%25A3%25AE%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2VlOWMzMWRhODMuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:Ubie%2520%25E3%2583%2586%25E3%2583%2583%25E3%2582%25AF%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2hwRUMxbUtjVjZsX01lT2R6N1Nsejk1SXR4WUZoYjB2LTNOdzNjV3c9czI1MC1j%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーの Gota@Data Analyst さん: 「Claude Code で Kiro の仕様駆動開発するための仕様書を作成する slash commands の大幅アップデート完了しました！ 主な変更点: ・Kiro の設計思想にさらに近い出力ができるように要件定義、詳細設計、タスク分解ドキュメントの品質&amp;安定性向上 ・承認フローをより簡単に実行可能に Github に置いてます https://t.co/2FotWG8qpG」 / X](https://x.com/gota_bara/status/1949215928736158100)

![XユーザーのGota@Data Analystさん: 「Claude CodeでKiroの仕様駆動開発するための仕様書を作成するslash commandsの大幅アップデート完了しました！  主な変更点: ・Kiroの設計思想にさらに近い出力ができるように要件定義、詳細設計、タスク分解ドキュメントの品質&安定性向上 ・承認フローをより簡単に実行可能に  Githubに置いてます https://t.co/2FotWG8qpG」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [gotalab/claude-code-spec: From prototype to production with Spec-Driven Development for Claude Code. Slash commands that enforce structured requirements→design→tasks workflow, transforming how you build with AI](https://github.com/gotalab/claude-code-spec)

![gotalab/claude-code-spec: From prototype to production with Spec-Driven Development for Claude Code. Slash commands that enforce structured requirements→design→tasks workflow, transforming how you build with AI](https://opengraph.githubassets.com/903012fb4a794d446259be684c94ae1e03382aa17939a15c05b5189f7755df30/gotalab/claude-code-spec)

From prototype to production with Spec-Driven Development for Claude Code. Slash commands that enforce structured requirements→design→tasks workflow, transforming how you build with AI - gotalab/cl...

---

### [X ユーザーの Gota@Data Analyst さん: 「Claude Code で使う https://t.co/iyBTMW5Zzd が長すぎてコンテキストウィンドウ圧迫してたので、簡潔にしました！ 正直コンテキストエンジニアリングってトライアンドエラーになるから時間が無限に溶けるぜ！（Manus のような KV キャッシュ率とかは考えなくて良いから楽ですが...）」 / X](https://x.com/gota_bara/status/1949667388519252368)

![XユーザーのGota@Data Analystさん: 「Claude Codeで使うhttps://t.co/iyBTMW5Zzd が長すぎてコンテキストウィンドウ圧迫してたので、簡潔にしました！  正直コンテキストエンジニアリングってトライアンドエラーになるから時間が無限に溶けるぜ！（ManusのようなKVキャッシュ率とかは考えなくて良いから楽ですが...）」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [kiro を参考にして作成した CLAUDE.md - izanami](https://izanami.dev/post/11c5067c-d2f9-4945-8944-0d1c20c1263d)

![kiroを参考にして作成したCLAUDE.md - izanami](https://izanami.dev/post/11c5067c-d2f9-4945-8944-0d1c20c1263d/opengraph-image-1umokf?5589478d64c13f8a)

非常にシンプルで、AI の暴走を防ぐルール。現状最適な CLAUDE.md。導入簡単、汎用性高。

---

### [Claude Code だけで Kiro 風をやる](https://zenn.dev/sosukesuzuki/articles/593903287631e9)

![Claude CodeだけでKiro風をやる](https://res.cloudinary.com/zenn/image/upload/s--dk4d3lSF--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25A0%25E3%2581%2591%25E3%2581%25A7Kiro%25E9%25A2%25A8%25E3%2582%2592%25E3%2582%2584%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Sosuke%2520Suzuki%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2kzVm5WZHo2MC1CT3lMTS1VVnZaNmdNSDJlTlp1T0lTa1owT3lyNnc9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code 最新のカスタムサブエージェント機能を試してみた](https://zenn.dev/acntechjp/articles/c558ca0d83ca88)

![Claude Code最新のカスタムサブエージェント機能を試してみた](https://res.cloudinary.com/zenn/image/upload/s--F-wr7Z98--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E6%259C%2580%25E6%2596%25B0%25E3%2581%25AE%25E3%2582%25AB%25E3%2582%25B9%25E3%2582%25BF%25E3%2583%25A0%25E3%2582%25B5%25E3%2583%2596%25E3%2582%25A8%25E3%2583%25BC%25E3%2582%25B8%25E3%2582%25A7%25E3%2583%25B3%25E3%2583%2588%25E6%25A9%259F%25E8%2583%25BD%25E3%2582%2592%25E8%25A9%25A6%25E3%2581%2597%25E3%2581%25A6%25E3%2581%25BF%25E3%2581%259F%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Hongbo.Ding%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2U2ZDA4MDY5ODcuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/g_south_west%2Ch_34%2Cl_default:og-publication-pro-mark-xcosax%2Cw_34%2Cx_217%2Cy_158/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:Accenture%2520Japan%2520%2528%25E6%259C%2589%25E5%25BF%2597%2529%2Cx_255%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzA4OTAxYWE5NWQuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code でカスタムサブエージェントを作成する](https://azukiazusa.dev/blog/create-custom-sub-agent-in-claude-code/)

![Claude Code でカスタムサブエージェントを作成する](https://azukiazusa.dev/blog/ogp/create-custom-sub-agent-in-claude-code.png)

Claude Code では特定の種類のタスクを処理するために呼び出されるカスタムサブエージェントを作成できます。カスタムサブエージェントを使用することでメインの会話セッションとは別に独立したコンテキストウィンドウを持つことができ、コンテキストの汚染を防ぐことができます。この記事では、Claude Code でカスタムサブエージェントを作成する方法とその利点について解説します。

---

### [X ユーザーの Oikon＠外資 IT エンジニアさん: 「【使い分け】 ・Subagent 🆕 以前 Task として実行していた機能。役割を明確化してツールを並列実行可能に ・Hooks 特定のタイミングで Bash コマンドなどを自動的に実行。通知や Linter など決まった動作向き ・カスタム Slash Command プロンプトの再利用。プロセスは決まっているが結果が不定の作業向き」 / X](https://x.com/gaishi_narou/status/1948580216533909657)

![XユーザーのOikon＠外資ITエンジニアさん: 「【使い分け】  ・Subagent 🆕 以前Taskとして実行していた機能。役割を明確化してツールを並列実行可能に  ・Hooks 特定のタイミングでBashコマンドなどを自動的に実行。通知やLinterなど決まった動作向き  ・カスタムSlash Command プロンプトの再利用。プロセスは決まっているが結果が不定の作業向き」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [[小ネタ]Claude Code の Sub agent でレビュー& pr にコメントさせる | DevelopersIO](https://dev.classmethod.jp/articles/claudecode-sugagent-github-pr/)

![[小ネタ]Claude Code のSub agentでレビュー& prにコメントさせる | DevelopersIO](https://images.ctfassets.net/ct0aopd36mqt/wp-thumbnail-75c24212db08a605cf51b1578f9a040c/f14b12b1b1cf9b5ed2427490ff86734d/eyecatch_anthropic)

---

### [Claude Code Sub agents で常に最新の技術選定を行わせる](https://zenn.dev/studio/articles/00c3002e93adb1)

![Claude Code Sub agentsで常に最新の技術選定を行わせる](https://res.cloudinary.com/zenn/image/upload/s--0ZqCNUT7--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%2520Sub%2520agents%25E3%2581%25A7%25E5%25B8%25B8%25E3%2581%25AB%25E6%259C%2580%25E6%2596%25B0%25E3%2581%25AE%25E6%258A%2580%25E8%25A1%2593%25E9%2581%25B8%25E5%25AE%259A%25E3%2582%2592%25E8%25A1%258C%25E3%2582%258F%25E3%2581%259B%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:miyaoka%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2UwYmNhNWZkODEuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:Studio%2520Tech%2520Blog%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2FlYTU4ZTc5ZDAuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code の問題解決能力の底上げを試みる：MCP サーバー + subagents](https://zenn.dev/oikon/articles/82c9a52dc45810)

![Claude Codeの問題解決能力の底上げを試みる：MCPサーバー + subagents](https://res.cloudinary.com/zenn/image/upload/s--cJdC36AG--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AE%25E5%2595%258F%25E9%25A1%258C%25E8%25A7%25A3%25E6%25B1%25BA%25E8%2583%25BD%25E5%258A%259B%25E3%2581%25AE%25E5%25BA%2595%25E4%25B8%258A%25E3%2581%2592%25E3%2582%2592%25E8%25A9%25A6%25E3%2581%25BF%25E3%2582%258B%25EF%25BC%259AMCP%25E3%2582%25B5%25E3%2583%25BC%25E3%2583%2590%25E3%2583%25BC%2520%252B%2520subagents%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Oikon%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzFlNjI2MjNlZTQuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーのゴリラ - ダイエットチャレンジ中さん: 「メモ Claude Code Actions で使われている prompt を抜き出した 後でサブエージェントを作る際に参考にする https://t.co/ewHLMcZRQh」 / X](https://x.com/gorilla0513/status/1948556036530733433)

![Xユーザーのゴリラ - ダイエットチャレンジ中さん: 「メモ Claude Code Actionsで使われているpromptを抜き出した 後でサブエージェントを作る際に参考にする https://t.co/ewHLMcZRQh」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Claude Code の公式 DevContainer について](https://zenn.dev/mixi/articles/c2a11b1765b149)

![Claude Codeの公式DevContainerについて](https://res.cloudinary.com/zenn/image/upload/s--UEv8oBb0--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AE%25E5%2585%25AC%25E5%25BC%258FDevContainer%25E3%2581%25AB%25E3%2581%25A4%25E3%2581%2584%25E3%2581%25A6%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:%25E3%2581%2597%25E3%2582%258D%25E3%2581%25A1%25E3%2582%2583%25E3%2582%2593%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2UzY2IwNWVmMTMuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/g_south_west%2Ch_34%2Cl_default:og-publication-pro-mark-xcosax%2Cw_34%2Cx_217%2Cy_158/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:MIXI%2520DEVELOPERS%2520Tech...%2Cx_255%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUNnOG9jSmdPdXkwaXpkYmFSWl90VWZQc2tlWWRFNWNiQjFZVzVSRDlyMk94QXNLcjAxd3IzSjI9czk2LWM=%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Dev Container で安全に claude code を使う - Qiita](https://qiita.com/nakamasato/items/77b1567914fe51d08525)

![Dev Containerで安全にclaude codeを使う - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Farticle-ogp-background-afbab5eb44e0b055cce1258705637a91.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnFpaXRhLWltYWdlLXN0b3JlLnMzLmFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkYwJTJGNzA1OSUyRnByb2ZpbGUtaW1hZ2VzJTJGMTY0MDMwMTAwMz9peGxpYj1yYi00LjAuMCZhcj0xJTNBMSZmaXQ9Y3JvcCZtYXNrPWVsbGlwc2UmYmc9RkZGRkZGJmZtPXBuZzMyJnM9ODBjMWM3Y2EzZmJlZmMzMjViMzliZjBmYWZjM2RhNWU%26blend-x%3D120%26blend-y%3D467%26blend-w%3D82%26blend-h%3D82%26blend-mode%3Dnormal%26s%3D75d87a58bd20d93f34365c8ab1e7b9f0?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9RGV2JTIwQ29udGFpbmVyJUUzJTgxJUE3JUU1JUFFJTg5JUU1JTg1JUE4JUUzJTgxJUFCY2xhdWRlJTIwY29kZSVFMyU4MiU5MiVFNCVCRCVCRiVFMyU4MSU4NiZ0eHQtYWxpZ249bGVmdCUyQ3RvcCZ0eHQtY29sb3I9JTIzMUUyMTIxJnR4dC1mb250PUhpcmFnaW5vJTIwU2FucyUyMFc2JnR4dC1zaXplPTU2JnR4dC1wYWQ9MCZzPTNkZTVkYzJkOTcyMGIzODBhMjNhNDA1NGQ0YzMxMTFm&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDBuYWthbWFzYXRvJnR4dC1jb2xvcj0lMjMxRTIxMjEmdHh0LWZvbnQ9SGlyYWdpbm8lMjBTYW5zJTIwVzYmdHh0LXNpemU9MzYmdHh0LXBhZD0wJnM9M2U2MmY5YzY2MzA5NTc1NmVjYTlhMGVkMmU4ODg4ZGI&blend-x=242&blend-y=480&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&s=d21e3f1e93cc4372fd3f4699949851b1)

まとめ Dev Container の中で Claude Code を起動することでプロジェクト内のファイルのみへのアクセスを許可することで意図しないファイルの変更・削除・作成などを避けることができます claude code の設定には以下の設定+~/.claude の永続化...

---

### [Claude Code + Container Use と Cursor で作る ローカル並列開発環境のススメ / ccc local dev](https://speakerdeck.com/kaelaela/ccc-local-dev)

![Claude Code + Container Use と Cursor で作る ローカル並列開発環境のススメ / ccc local dev](https://files.speakerdeck.com/presentations/9fa8026d6516463b9d0b9e27bd86d143/slide_0.jpg?35765948)

<a href="https://kaelae.la" target="_blank" rel="noopener noreferrer">プロフィール</a>
<a href="https://dagger.io/blog/agent-container-use" target="\_blank" r&hellip;

---

### [複数の Gemini CLI が同時開発する狂気 - Jujutsu が実現する AI エージェント協調の新世界](https://speakerdeck.com/gunta/fu-shu-nogemini-cligatong-shi-kai-fa-surukuang-qi-jujutsugashi-xian-suruaiezientoxie-diao-noxin-shi-jie)

![複数のGemini CLIが同時開発する狂気 - Jujutsuが実現するAIエージェント協調の新世界](https://files.speakerdeck.com/presentations/5a18655ae8f04c9face1985b4536b737/slide_0.jpg?36001099)

Google の経験から生まれた次世代 VCS「Jujutsu」が、真の並列 AI 開発を可能にする方法をご紹介します。複数の Gemini CLI エージェントがコンフリクトなしで同時に作業し、10 倍の生産性向上を実現する手法を解説。

本講演の内容：
• 従来の Git ワークフローが AI エージェントのボトル&hellip;

---

### [X ユーザーの Oikon＠外資 IT エンジニアさん: 「Claude Code の Subagents をまとめたリポジトリありそうだなー、と思って探してみたら何個かあった。 完全に真似するかは置いておいて、他の人がどういう Subagents を作っているかの参考になりそう ↓ https://t.co/3rPQz6yz6O」 / X](https://x.com/gaishi_narou/status/1950025126856007774)

![XユーザーのOikon＠外資ITエンジニアさん: 「Claude CodeのSubagentsをまとめたリポジトリありそうだなー、と思って探してみたら何個かあった。  完全に真似するかは置いておいて、他の人がどういうSubagentsを作っているかの参考になりそう↓ https://t.co/3rPQz6yz6O」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Jujutsu（jj）完全ガイド：Git を超える次世代バージョン管理システムの実践活用法](https://zenn.dev/kimkiyong/articles/1806beccb74a88)

![Jujutsu（jj）完全ガイド：Gitを超える次世代バージョン管理システムの実践活用法](https://res.cloudinary.com/zenn/image/upload/s--U0DE9dzd--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Jujutsu%25EF%25BC%2588jj%25EF%25BC%2589%25E5%25AE%258C%25E5%2585%25A8%25E3%2582%25AC%25E3%2582%25A4%25E3%2583%2589%25EF%25BC%259AGit%25E3%2582%2592%25E8%25B6%2585%25E3%2581%2588%25E3%2582%258B%25E6%25AC%25A1%25E4%25B8%2596%25E4%25BB%25A3%25E3%2583%2590%25E3%2583%25BC%25E3%2582%25B8%25E3%2583%25A7%25E3%2583%25B3%25E7%25AE%25A1%25E7%2590%2586%25E3%2582%25B7%25E3%2582%25B9%25E3%2583%2586%25E3%2583%25A0%25E3%2581%25AE%25E5%25AE%259F%25E8%25B7%25B5%25E6%25B4%25BB%25E7%2594%25A8%25E6%25B3%2595%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%258D%25E3%2582%2587%25E3%2582%2593%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzZlNGVhN2QzODAuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーの生ビールさん: 「gemini-cli さん、すいませんいつの間にか対応されてたのですね。 https://t.co/FkzjztIPt5. https://t.co/GjxqUi6LLe」 / X](https://x.com/wmoto_ai/status/1948240929413861693)

![Xユーザーの生ビールさん: 「gemini-cliさん、すいませんいつの間にか対応されてたのですね。 https://t.co/FkzjztIPt5. https://t.co/GjxqUi6LLe」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーのわたヤク@AI 臨床研究さん: 「作図における神ツール「Draw.​io」ですが、VS Code の拡張機能『Draw.​io Integration』を入れることでローカルで動かせるだけでなく、何と Gemini CLI を使って自然言語で作図できちゃいます。引用してる方法で手書きメモから図への変換も可能。画像は患者フロー図の日本語文章を英語に変換したところ。 https://t.co/2bS37YctGl」 / X](https://x.com/ai_biostat/status/1949799920703074787)

![Xユーザーのわたヤク@AI臨床研究さん: 「作図における神ツール「Draw.​io」ですが、VS Codeの拡張機能『Draw.​io Integration』を入れることでローカルで動かせるだけでなく、何とGemini CLIを使って自然言語で作図できちゃいます。引用してる方法で手書きメモから図への変換も可能。画像は患者フロー図の日本語文章を英語に変換したところ。 https://t.co/2bS37YctGl」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Claude Code 再入門](https://speakerdeck.com/schroneko/re-introduction-to-claude-code)

![Claude Code 再入門](https://files.speakerdeck.com/presentations/3f36af6d243143839c697f12111e083c/slide_0.jpg?35930157)

---

### [Claude Code を実務開発で使い倒して得られた知見](https://tonkotsuboy.github.io/20250731-forkwell-claude-code/#1)

![Claude Codeを実務開発で使い倒して得られた知見](https://tonkotsuboy.github.io/20250731-forkwell-claude-code/images/cover.png)

Claude Code がチームに導入されて以来、開発の中心ワークフローに Claude Code が据えられました。本セッションでは、どのように実務で Claude Code を使っているか、その中で得られた知見とともに紹介します。

---

### [実務で使っている Claude Code の活用事例集 - Claude Code Meetup](https://tonkotsuboy.github.io/20250717-findy-claudecode/#1)

![実務で使っているClaude Codeの活用事例集 - Claude Code Meetup](https://tonkotsuboy.github.io/20250717-findy-claudecode/images/cover.png)

Hooks、カスタムスラッシュコマンド、MCP、Aqua Voice 連携、Kiro 連携など、Claude Code をより効率的に使うための実践的なテクニックを紹介します。

---

### [X ユーザーの Kinopee / きのぴーさん: 「Vibe coding in prod（本番環境でのバイブコーディング ） 最近、たびたび議論になるバイブコーディングに関する Anthropic エンジニアによる解説。 https://t.co/e4TzSM4SaY」 / X](https://x.com/kinopee_ai/status/1951507567181779312)

![XユーザーのKinopee / きのぴーさん: 「Vibe coding in prod（本番環境でのバイブコーディング ） 最近、たびたび議論になるバイブコーディングに関する Anthropic エンジニアによる解説。 https://t.co/e4TzSM4SaY」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの Oikon＠外資 IT エンジニアさん: 「海外の Claude Code Tips: • /init でコードスキャン • Kiro の Spec-driven 開発を採用 • Hooks (post_tool)で型チェック • カスタムコマンドで SuperClaude(OSS)を使用 • /resume/export で Cursor と併用 • ccundo/yoyo(OSS）で変更を元に戻す • .zshrc の BASE_URL 変更で Kimi に接続する」 / X](https://x.com/gaishi_narou/status/1948409818420830374)

![XユーザーのOikon＠外資ITエンジニアさん: 「海外のClaude Code Tips:  •  /initでコードスキャン •  KiroのSpec-driven開発を採用 •  Hooks (post_tool)で型チェック •  カスタムコマンドでSuperClaude(OSS)を使用 •  /resume/exportでCursorと併用 •  ccundo/yoyo(OSS）で変更を元に戻す •  .zshrcのBASE_URL変更でKimiに接続する」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Claude Code がアホになる問題](https://blog.lai.so/cc-dumber/)

最近一部の Claude Code ユーザーの間で「性能が急激に劣化している」という報告が多発しています。具体的には、指示の内容を忘れて見当違いの作業をするというもので「これは Claude Code のコンテキスト処理の問題ではないか？」と憶測を呼んでいます。

※この話題はバージョン 1.0.63 時点のものです。

「バージョン 1.0.24 に固定せよ」

この問題に対して、ユーザーからの報告と対処法が以下で説明されています。

Critical: Claude Code context amnesia causes silent code deletion · Issue #4487 · anthropics/claude-codeEnvironment Platform: Claude Code CLI Claude CLI version: 1.0.61 Operating System: macOS 15.5 (Build 24F74) Terminal: Terminal App

---

### [Claude Code による生産性向上の限界｜ suthio](https://note.com/suthio/n/n45a179642d7d?sub_rt=share_pb)

![Claude Codeによる生産性向上の限界｜suthio](https://assets.st-note.com/production/uploads/images/204890426/rectangle_large_type_2_0453e9e90d9993e45b8839e13a95c9c0.png?fit=bounds&quality=85&width=1280)

最近、Claude Code を使っている人から「レビューが追いつかない」という相談をよく受ける。これは偶然ではなく、必然的に起きる現象だと考えています。 この note では どうして Claude Code による生産性向上の限界が訪れるのか どうすれば、全体の生産性が向上するのか Claude Code を利用した場合にレビュープロセスでのボトルネックをどのように解消させていくか の 3 つを書いていきます。 プロダクト開発の典型的なワークフロー まず、多くのチームで採用されている機能追加のワークフローを整理してみる。 ※あくまで一般例なので、チームにより変更があ

---

### [Claude Code で常にコンテクスト残量を表示する方法](https://zenn.dev/ml0_1337/articles/012da05fa06b9e)

![Claude Codeで常にコンテクスト残量を表示する方法](https://res.cloudinary.com/zenn/image/upload/s--yZXoKpYJ--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25A7%25E5%25B8%25B8%25E3%2581%25AB%25E3%2582%25B3%25E3%2583%25B3%25E3%2583%2586%25E3%2582%25AF%25E3%2582%25B9%25E3%2583%2588%25E6%25AE%258B%25E9%2587%258F%25E3%2582%2592%25E8%25A1%25A8%25E7%25A4%25BA%25E3%2581%2599%25E3%2582%258B%25E6%2596%25B9%25E6%25B3%2595%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2583%259F%25E3%2583%25AD%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2EwOWEyYzEwNTcuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [プログラミング自動化の果てに](https://aoai-ai-coding.mizchi.workers.dev/#1)

---

### [claude code に NG Word 集を設定すればキレなくてすむのでそのやり方](https://zenn.dev/sesere/articles/e3d5695e0a7d14)

![claude codeにNG Word集を設定すればキレなくてすむのでそのやり方](https://res.cloudinary.com/zenn/image/upload/s--gtpkHpRR--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:claude%2520code%25E3%2581%25ABNG%2520Word%25E9%259B%2586%25E3%2582%2592%25E8%25A8%25AD%25E5%25AE%259A%25E3%2581%2599%25E3%2582%258C%25E3%2581%25B0%25E3%2582%25AD%25E3%2583%25AC%25E3%2581%25AA%25E3%2581%258F%25E3%2581%25A6%25E3%2581%2599%25E3%2582%2580%25E3%2581%25AE%25E3%2581%25A7%25E3%2581%259D%25E3%2581%25AE%25E3%2582%2584%25E3%2582%258A%25E6%2596%25B9%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:sesere%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzg4NjY3ZDcwMjMuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーのゴリラ - ダイエットチャレンジ中さん: 「メモ ケントベックの CLAUDE\.md https://t.co/HVs93NftQs」 / X](https://x.com/gorilla0513/status/1943088128648188150)

![Xユーザーのゴリラ - ダイエットチャレンジ中さん: 「メモ ケントベックのCLAUDE.md  https://t.co/HVs93NftQs」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [【Claude MAX】GitHubActions で動作する Claude Code から PR レビュー結果を MCP で Slack に](https://zenn.dev/mohy_nyapan/articles/3d20c9979c9b2f)

![【Claude MAX】GitHubActionsで動作するClaude CodeからPRレビュー結果をMCPでSlackに](https://res.cloudinary.com/zenn/image/upload/s--hUIwWpRQ--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E3%2580%2590Claude%2520MAX%25E3%2580%2591GitHubActions%25E3%2581%25A7%25E5%258B%2595%25E4%25BD%259C%25E3%2581%2599%25E3%2582%258BClaude%2520Code%25E3%2581%258B%25E3%2582%2589PR%25E3%2583%25AC%25E3%2583%2593%25E3%2583%25A5%25E3%2583%25BC%25E7%25B5%2590%25E6%259E%259C%25E3%2582%2592MCP%25E3%2581%25A7S...%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2583%25A2%25E3%2583%2592%25E3%2581%25AB%25E3%2582%2583%25E3%2581%25B1%25E3%2582%2593%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2FjYzVlOGJiNjkuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Vibe coding コードレビュー](https://speakerdeck.com/kinopeee/vibe-coding-kodorebiyu)

![Vibe coding コードレビュー](https://files.speakerdeck.com/presentations/bd6f717017b34e07928ad2caf012861b/slide_0.jpg?36114815)

---

### [AI エージェントのためのコンテキストエンジニアリング：Manus 構築から得た教訓](https://manus.im/ja/blog/Context-Engineering-for-AI-Agents-Lessons-from-Building-Manus)

![AIエージェントのためのコンテキストエンジニアリング：Manus構築から得た教訓](https://files.manuscdn.com/assets/dashboard/materials/2025/07/18/eaafe9e6a174b29458c314ccc225dbdd39a7c9d66e60786235165d9aba23f578.webp)

この投稿は、私たち自身の「SGD」を通じて Manus が到達した局所的最適解を共有しています。あなたが自分自身の AI エージェントを構築している場合、これらの原則があなたのより速い収束に役立つことを願っています。

---

### [X ユーザーのテツメモ｜ AI 図解 × 検証｜ Newsletter さん: 「📝 いや、これ公開して良いの？と思うレベルで有益 Manus が「AI エージェントのためのコンテキストエンジニアリング：Manus 構築から得た教訓」を大公開 なぜ Manus がユーザーの指示（目的）を忠実に実行して理想のゴールに導くことができるのか 6 つのスライドでまとめました　 👇️ https://t.co/zpZUFwzKPM」 / X](https://x.com/tetumemo/status/1946555324875575474)

![Xユーザーのテツメモ｜AI図解×検証｜Newsletterさん: 「📝いや、これ公開して良いの？と思うレベルで有益  Manusが「AIエージェントのためのコンテキストエンジニアリング：Manus構築から得た教訓」を大公開  なぜManusがユーザーの指示（目的）を忠実に実行して理想のゴールに導くことができるのか  6つのスライドでまとめました　👇️ https://t.co/zpZUFwzKPM」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

## MCP

### [Serena MCP は Claude Code を救うのか？](https://blog.lai.so/serena/)

「Claude Code がアホになる問題」が勃発している最中、Serena という MCP サーバーが「Claude Code のコンテキスト消費を削減し、応答を改善する」という評価でユーザーたちの間で注目されています。

筆者も実際に Serena を使ってみたところ、確かにコンテキスト効率の改善（入出力トークンの減少を指します）を実感できました。詳しく調べてみると、このツールは非常にユニークな発想で設計されており、一過性の流行として消費されるには惜しいと感じました。

そこで、本記事では、この機能の背景にある技術的な仕組みを詳しく解説したいと思います。実際の検証も交えながら、Serena のアーキテクチャとその効果を分析していきます。

現在のコーディングエージェントが抱える課題

現在のコーディングエージェントの多くは、コードを単なるテキストファイルとして扱って逐次的な処理をしています。この根本的なアプローチが、制約を生み出しています。

大規模なプロジェクトで作業する際、エージェントは必要な情報を見つけるために膨大なテキストを読み込まなければなりません。関数の定義を探すだけでも、リポジトリ

---

### [コーディングエージェントの能力を拡張する Serena を試してみた](https://azukiazusa.dev/blog/serena-coding-agent/)

![コーディングエージェントの能力を拡張する Serena を試してみた](https://azukiazusa.dev/blog/ogp/serena-coding-agent.png)

LSP を活用してセマンティックなコード検索・編集能力を提供する MCP サーバー Serena の導入・使用方法を紹介。Claude Code でのオンボーディングからリファクタリングまでの実践的な活用例を解説します。

---

### [AI コーディングの常識が変わる！Claude を"覚醒"させる知性、「Serena」徹底解説｜ Kyutaro](https://note.com/kyutaro15/n/n61a8825fe303)

![AIコーディングの常識が変わる！Claudeを"覚醒"させる知性、「Serena」徹底解説｜Kyutaro](https://assets.st-note.com/production/uploads/images/205122974/rectangle_large_type_2_ce1858183180980f2a8f41fea60c088f.png?fit=bounds&quality=85&width=1280)

AI を使ってコーディングをしていると、こんな風に感じたことはありませんか？ 「大きなファイルを読み込ませるたびに、大量のトークンが消費されてしまう…💸」 「1 つのバグを直してもらったら、別の 3 つのバグが生まれてしまった…😭」 「AI がコードの全体像を理解してくれなくて、何度も同じ説明を繰り返している…🌀」 これらの悩みは、AI がコードを「テキストの羅列」としてしか見られていないことに起因します。しかし、もし AI が人間のようにコードの「意味」や「構造」を理解してくれたら…？ 今回は、そんな夢のような未来を実現するツール「Serena」について、その魅力と使い方を、AI 技術に触れ

---

### [Claude Code を 10 倍賢くする無料ツール「Serena」の威力とトークン効率化術](https://zenn.dev/sc30gsw/articles/ff81891959aaef)

![Claude Codeを10倍賢くする無料ツール「Serena」の威力とトークン効率化術](https://res.cloudinary.com/zenn/image/upload/s--yHQtMoEe--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2582%259210%25E5%2580%258D%25E8%25B3%25A2%25E3%2581%258F%25E3%2581%2599%25E3%2582%258B%25E7%2584%25A1%25E6%2596%2599%25E3%2583%2584%25E3%2583%25BC%25E3%2583%25AB%25E3%2580%258CSerena%25E3%2580%258D%25E3%2581%25AE%25E5%25A8%2581%25E5%258A%259B%25E3%2581%25A8%25E3%2583%2588%25E3%2583%25BC%25E3%2582%25AF%25E3%2583%25B3%25E5%258A%25B9%25E7%258E%2587%25E5%258C%2596%25E8%25A1%2593%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:kaito%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzA5ZmViMGZmOGUuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーのえいと｜ n8n 効率化職人さん: 「個人開発者は絶対これ使って。Claude Code が 10 倍強力になります。「Code Context」は、Claude Code・Gemini CLI などに深い文脈理解と正確なコード生成を与える MCP プラグインです。しかも 100%オープンソース。具体的な活用例を紹介するので絶対保存して 👇 https://t.co/P0l1bQFas5」 / X](https://x.com/7_eito_7/status/1950051185559323032)

![Xユーザーのえいと｜n8n効率化職人さん: 「個人開発者は絶対これ使って。Claude Codeが10倍強力になります。「Code Context」は、Claude Code・Gemini CLIなどに深い文脈理解と正確なコード生成を与えるMCPプラグインです。しかも100%オープンソース。具体的な活用例を紹介するので絶対保存して👇 https://t.co/P0l1bQFas5」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [o3 MCP で Claude Code が最強の検索力を手に入れた](https://zenn.dev/yoshiko/articles/claude-code-with-o3)

![o3 MCPでClaude Codeが最強の検索力を手に入れた](https://res.cloudinary.com/zenn/image/upload/s--xAYvgHwM--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:o3%2520MCP%25E3%2581%25A7Claude%2520Code%25E3%2581%258C%25E6%259C%2580%25E5%25BC%25B7%25E3%2581%25AE%25E6%25A4%259C%25E7%25B4%25A2%25E5%258A%259B%25E3%2582%2592%25E6%2589%258B%25E3%2581%25AB%25E5%2585%25A5%25E3%2582%258C%25E3%2581%259F%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2582%2588%25E3%2581%2597%25E3%2581%2593%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2kwU3JDUjBpVERyUHpqWnF4YjJLZ0tueHgtamE0N253SEE0NGE4RDhrPXMyNTAtYw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [降霊術で t_wada を AI に降ろして PR レビューして貰うテクニックが伸びたのでその裏側記事を書きました！｜ Ryo@VibeCoder](https://note.com/biwakonbu/n/n0f1c75418030?sub_rt=share_sb)

![降霊術で t_wada を AI に降ろして PR レビューして貰うテクニックが伸びたのでその裏側記事を書きました！｜Ryo@VibeCoder](https://assets.st-note.com/production/uploads/images/199784473/rectangle_large_type_2_7480a2563a5f78f8aae1e6e36a6d5664.png?fit=bounds&quality=85&width=1280)

最近 X（旧 Twitter）では「t*wada の TDD で進めてください」という一言で、テスト駆動の意図を一気に共有する"圧縮プロンプト"がバズっていますよね。 この流れをさらに一歩進め、 AI に TDD をさせるのではなく、t_wada 本人を降霊させて "レビュー" をもらう という実験を行い、その結果をポストしたらご本人に言及頂き、インプレッションが非常に大きくなり、注目されました。 例のポスト みんな t_wada メソッドを TDD で進めるのに使ってるけど自分は PR やコード、テストの品質レビュー、リファクタリングのためのテスト網羅性のレビューなどに t*

---

### [Claude 向け人名＋テクニック一覧(t_wada さんの TDD など) - くらげになりたい。](https://www.memory-lovers.blog/entry/2025/06/27/102550)

![Claude向け人名＋テクニック一覧(t_wadaさんのTDDなど) - くらげになりたい。](https://ogimage.blog.st-hatena.com/12921228815718008255/6802418398489574531/1750987550)

このあたりのツイートを見て、よいなとおもったので、 Claude さんにリストアップしてもらった(_´ω ｀_) 「t_wada さんの TDD」など、人名を追加すると精度がよいっぽい Claude Code に TDD を実行させたいとき、「t-wada の推奨する進め方に従ってください」がめっちゃ効く— hori (@hori_ryota) June 23, 2025 TDD だけでなく「リファクタリング」も意味の希薄化が激しいので、AI に「リファクタリングして」と指示しても効き目がいまいちなことが多々ある。これも人名を出して文脈を境界付けるのが面白そう。「Fowler の」とか「Kent Beck の Ti…

---

## AI エージェント

### [Claude Code が働く AI 中心の業務システム構築の挑戦―AI エージェント中心の働き方を目指して](https://speakerdeck.com/os1ma/claude-codegadong-kuaizhong-xin-noye-wu-sisutemugou-zhu-notiao-zhan-aiezientozhong-xin-nodong-kifang-womu-zhi-site)

![Claude Codeが働くAI中心の業務システム構築の挑戦―AIエージェント中心の働き方を目指して](https://files.speakerdeck.com/presentations/9bbee7bd53ee48b88c58b5c888f13351/slide_0.jpg?36114359)

Claude Code をはじめとするコーディングエージェントの盛り上がりは凄まじく、ソフトウェア開発でのさまざまな活用事例が出てきています。

実は Claude Code などのコーディングエージェントは、ソフトウェア開発以外のタスクにも活用することができます。

実際に登壇者は、Claude C&hellip;

---

## 気になるツール/サービス 1(開発/情報系)

### [X ユーザーの梶谷健人 / POSTS さん: 「Claude が Canva と連携して任意のドキュメントをデザインされた資料に変換できるようになった。 これスライド生成もそのうちやってくるな。 https://t.co/Kv9pXi787Y」 / X](https://x.com/kajikent/status/1948548079722135893)

![Xユーザーの梶谷健人 / POSTSさん: 「ClaudeがCanvaと連携して任意のドキュメントをデザインされた資料に変換できるようになった。  これスライド生成もそのうちやってくるな。  https://t.co/Kv9pXi787Y」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Figma to Code の AI ツール「Kombai」を使ってみた](https://zenn.dev/oikon/articles/kombai-frontend)

![Figma to CodeのAIツール「Kombai」を使ってみた](https://res.cloudinary.com/zenn/image/upload/s--57Sas4iz--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Figma%2520to%2520Code%25E3%2581%25AEAI%25E3%2583%2584%25E3%2583%25BC%25E3%2583%25AB%25E3%2580%258CKombai%25E3%2580%258D%25E3%2582%2592%25E4%25BD%25BF%25E3%2581%25A3%25E3%2581%25A6%25E3%2581%25BF%25E3%2581%259F%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Oikon%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzFlNjI2MjNlZTQuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [classmethod/tsumiki: tsumiki](https://github.com/classmethod/tsumiki)

![classmethod/tsumiki: tsumiki](https://opengraph.githubassets.com/ebf6f958d94a3b7389e4f2a59eeddce6f497f664bb2ad8e82a04e537f3232302/classmethod/tsumiki)

tsumiki. Contribute to classmethod/tsumiki development by creating an account on GitHub.

---

### [v0 の SDK を試してみる](https://azukiazusa.dev/blog/try-v0-sdk/)

![v0 の SDK を試してみる](https://azukiazusa.dev/blog/ogp/try-v0-sdk.png)

v0 は Vercel が開発した AI ベースの Web アプリケーション・UI 生成ツールです。v0 のプラットフォーム API を使用すると、v0 の機能を自身のコードから利用できます。この記事では v0 TypeScript SDK を使用して、v0 のプラットフォーム API を試してみます。

---

### [私のシンプルな CodeRabbit の使い方｜ニケちゃん](https://note.com/nike_cha_n/n/n046cbb65e2e0)

![私のシンプルなCodeRabbitの使い方｜ニケちゃん](https://assets.st-note.com/production/uploads/images/190067156/rectangle_large_type_2_2e0f14cbb74bd2904519e459f5986834.png?fit=bounds&quality=85&width=1280)

こんにちは、ニケです。 皆さん、CodeRabbit&nbsp;使っていますでしょうか？ CodeRabbit はいわゆるコードのレビューサービスで、私はかれこれ 1 年くらい使っています。 ただ、便利な割にあまり話題になっていないので、今回は紹介がてら使い方を説明していきたいと思います。 ちなみに、CodeRabbit はパブリックなリポジトリなら無料です。やばいですよね。 私は基本的に開発しているコードは OSS として公開しているので、タダで高品質なレビューを受けることができてかなり助かっています。 有償版は月$15 からのようです。 詳しくは下記からご確認ください。

AI Co

---

## 気になるツール/サービス 2(画像/動画/3D/音声/音楽生成、認識技術、XR/ゲーム関連等)

### [X ユーザーの田中義弘 | taziku CEO / AI × Creative さん: 「スマホやウェアラブルでリアルタイム AI が動く時代が来た ── 新モデル「RF-DETR nano」は、最新 YOLO より 11mAP 高精度＆0.17ms 高速。 しかも極小サイズで、低スペック端末でもリアルタイム物体検出が可能。 これは AR・スマートグラス・IoT 全ての“目”になる。 https://t.co/R5TTMwYKgb」 / X](https://x.com/taziku_co/status/1949031505394831539)

![Xユーザーの田中義弘 | taziku CEO / AI × Creativeさん: 「スマホやウェアラブルでリアルタイムAIが動く時代が来た──  新モデル「RF-DETR nano」は、最新YOLOより11mAP高精度＆0.17ms高速。 しかも極小サイズで、低スペック端末でもリアルタイム物体検出が可能。  これはAR・スマートグラス・IoT全ての“目”になる。 https://t.co/R5TTMwYKgb」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Aivis Project | AivisSpeech でかんたんに感情豊かな音声合成、使ってみませんか？](https://aivis-project.com/)

![Aivis Project | AivisSpeech でかんたんに感情豊かな音声合成、使ってみませんか？](https://aivis-project.com/assets/images/ogp.png)

Aivis Project は、感情豊かな音声合成技術を誰もがかんたんに活用できる未来を目指す、壮大な開発プロジェクトです。AivisSpeech を使えば、物語の朗読やニュース記事の読み上げなど、あなたの想いを魅力的な声で表現できます。音声合成の新しい可能性を、一緒に探求してみませんか？

---

### [ベータ無料！Aivis Cloud API を使ってバイブサンプル作ったらレイテンシーがやばかった！](https://zenn.dev/mohy_nyapan/articles/bc1dfee0501c7d)

![ベータ無料！Aivis Cloud APIを使ってバイブサンプル作ったらレイテンシーがやばかった！](https://res.cloudinary.com/zenn/image/upload/s--RO4SHWhU--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E3%2583%2599%25E3%2583%25BC%25E3%2582%25BF%25E7%2584%25A1%25E6%2596%2599%25EF%25BC%2581Aivis%2520Cloud%2520API%25E3%2582%2592%25E4%25BD%25BF%25E3%2581%25A3%25E3%2581%25A6%25E3%2583%2590%25E3%2582%25A4%25E3%2583%2596%25E3%2582%25B5%25E3%2583%25B3%25E3%2583%2597%25E3%2583%25AB%25E4%25BD%259C%25E3%2581%25A3%25E3%2581%259F%25E3%2582%2589%25E3%2583%25AC%25E3%2582%25A4%25E3%2583%2586%25E3%2583%25B3%25E3%2582%25B7%25E3%2583%25BC%25E3%2581%258C%25E3%2582%2584%25E3%2581%25B0%25E3%2581%258B%25E3%2581%25A3%25E3%2581%259F%25EF%25BC%2581%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2583%25A2%25E3%2583%2592%25E3%2581%25AB%25E3%2582%2583%25E3%2581%25B1%25E3%2582%2593%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2FjYzVlOGJiNjkuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [「Silero VAD」を試す](https://zenn.dev/kun432/scraps/f1b92c6510c87f)

![「Silero VAD」を試す](https://lh3.googleusercontent.com/a-/AOh14Gj2-TWBIJGuFBxhPY_QFO7z0tZ3sGpJSf9rPLKPLg=s250-c)

kun432 さんのスクラップ

---

### [リアルタイムアニメーションプラットフォーム](https://www.animation.inc/jp/)

![リアルタイムアニメーションプラットフォーム](https://framerusercontent.com/images/Y3G8iB693lFsZZjyKFgPxIHkQ8.png)

インタラクティブ生成アニメーション

---

### [Unity AI を試してみる（Unity 6.2 Beta 版を利用）｜オレンジ](https://note.com/a_orange/n/n760775d06c46)

![Unity AIを試してみる（Unity 6.2 Beta版を利用）｜オレンジ](https://assets.st-note.com/production/uploads/images/190824773/rectangle_large_type_2_4f7b4fd3e784415540ddf69fec520910.png?fit=bounds&quality=85&width=1280)

はじめに Unity AI は、Unity エディタ上でゲーム開発者向けに提供される AI を活用した様々な支援機能です。 本ノートでは UnityAI の基本的な使い方を記載します。 今回は、最新の Unity 6.2 Beta 版 を利用して、Unity AI を実際に触ってみたので、基本的な使い方などをまとめたいと思います。 Unity6.2Beta が公開 ✨️ AI 機能が無料で使えるポイントが付与される（Beta 版の間）のでお試し 生成オブジェクトのクオリティは発展途上ですが、ゲーム開発スピードを加速させるポテンシャルを感じました！ ※AI 作成：テクスチャ：表示画像、マテリアル：髪、アニメ

---

### [X ユーザーの田中義弘 | taziku CEO / AI × Creative さん: 「3D モデルがボタンひとつで A/T ポーズになる! Meshy の新機能で、画像や 3D モデルを「A/T ポーズ」で生成可能に。リギングに最適化され、すぐに動かせる人型モデルが手に入る。 ゲーム開発者、アニメーター、VTuber 制作者 ── 待望のアップデート https://t.co/IJIZfeRCE8」 / X](https://x.com/taziku_co/status/1950309678199820500)

![Xユーザーの田中義弘 | taziku CEO / AI × Creativeさん: 「3DモデルがボタンひとつでA/Tポーズになる!  Meshyの新機能で、画像や3Dモデルを「A/Tポーズ」で生成可能に。リギングに最適化され、すぐに動かせる人型モデルが手に入る。  ゲーム開発者、アニメーター、VTuber制作者──待望のアップデート https://t.co/IJIZfeRCE8」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

## その他

### [【CEDEC2025 フォローアップ】LLM を活用したゲーム開発支援と、生成 AI の利活用を進める組織的な取り組み](https://tech.cygames.co.jp/archives/3669/)

![【CEDEC2025 フォローアップ】LLMを活用したゲーム開発支援と、生成AIの利活用を進める組織的な取り組み](https://tech.cygames.co.jp/wp-content/uploads/2015/07/cygames.jpg)

---

### [Web サービス公開前のチェックリスト](https://zenn.dev/catnose99/articles/547cbf57e5ad28)

![Webサービス公開前のチェックリスト](https://res.cloudinary.com/zenn/image/upload/s--A6JiacKH--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Web%25E3%2582%25B5%25E3%2583%25BC%25E3%2583%2593%25E3%2582%25B9%25E5%2585%25AC%25E9%2596%258B%25E5%2589%258D%25E3%2581%25AE%25E3%2583%2581%25E3%2582%25A7%25E3%2583%2583%25E3%2582%25AF%25E3%2583%25AA%25E3%2582%25B9%25E3%2583%2588%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:catnose%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzc2YzYxNGExZmEuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [「良さそう」と「とても良い」の間には 「良さそうだがホンマか」がたくさんある / 2025.07.01 LLM 品質 Night](https://speakerdeck.com/smiyawaki0820/2025-dot-07-dot-01-llmpin-zhi-night)

![「良さそう」と「とても良い」の間には 「良さそうだがホンマか」がたくさんある / 2025.07.01  LLM品質Night](https://files.speakerdeck.com/presentations/aeb80953416b455a8586bfdeaa7a4c4e/slide_0.jpg?35671658)

こちらのイベントで登壇した資料になります。
LLM 品質 Night — Algomatic・PharmaX に学ぶ AI プロダクト品質の真髄 —
https://connpass.com/event/359656/

7/16(水) 19:30~ AI エージェント実践入門本 出版イベント @オンライ&hellip;

---

### [AI 技術(cursor pro, claude3.5/3.7)によってコーディング開発が 19%遅くなっている？！](https://zenn.dev/boku_yaji/articles/2eba9ff05fc3e2)

![AI技術(cursor pro, claude3.5/3.7)によってコーディング開発が19%遅くなっている？！](https://res.cloudinary.com/zenn/image/upload/s--7v9aX9mS--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:AI%25E6%258A%2580%25E8%25A1%2593%2528cursor%2520pro%252C%2520claude3.5%252F3.7%2529%25E3%2581%25AB%25E3%2582%2588%25E3%2581%25A3%25E3%2581%25A6%25E3%2582%25B3%25E3%2583%25BC%25E3%2583%2587%25E3%2582%25A3%25E3%2583%25B3%25E3%2582%25B0%25E9%2596%258B%25E7%2599%25BA%25E3%2581%258C19%2525%25E9%2581%2585%25E3%2581%258F%25E3%2581%25AA%25E3%2581%25A3%25E3%2581%25A6%25E3%2581%2584%25E3%2582%258B%25EF%25BC%259F%25EF%25BC%2581%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:boku-yaji%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2FkYjdmZTVjOWIuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code と Gemini CLI で登壇資料を作ってみた](https://speakerdeck.com/schroneko/vibe-sliding)

![Claude Code と Gemini CLI で登壇資料を作ってみた](https://files.speakerdeck.com/presentations/f3b4fa17d12b46e2a39cac5c0984a204/slide_0.jpg?35910594)

2025 年 7 月 16 日に開催された「Claude Code 派？Gemini CLI 派？ みんなで比較 LT 会！」登壇資料

https://connpass.com/event/360553/

---

### [ソリューションとして AI エージェントを売るのがなぜ難しいのか｜しば田](https://note.com/keisuke_shibata/n/ne35fb5cb3893)

![ソリューションとしてAIエージェントを売るのがなぜ難しいのか｜しば田](https://assets.st-note.com/production/uploads/images/203691860/rectangle_large_type_2_def9637c234ebc1136d5c1671a75129b.png?fit=bounds&quality=85&width=1280)

この記事は音声入力した内容を AI に整形してもらった上で再度人力で校正しています。 はじめに （遅ればせながら）今期から AI エージェントの受託開発の営業を開始しました。 結論、引きはあるので商談は取れるが、その先の本開発フェーズに進むことは中々難しいということが分かってきました。複数社と話す中で、共通のパターンもある程度見えてきたので、（まだ数ヶ月の試行錯誤なので解像度は浅いかとも思いますが）思考の整理も兼ねて書き記します。 注意：ここでいう「AI エージェント」とは、完全自立型ではなく、「AI ワークフロー」「Agentic ワークフロー」のことを指しています。 時短したい方向けの

---
