# このページについて

- 2025/06/4 から 2025/07/08 の期間で、個人的に気になった AI ニュース/記事/ポストなど。
- まとめる時間がなかったので、一旦 X のいいねから抜粋。いつもは、軽く目を通してここから絞り込んだりカテゴリ分けしてまとめています。

## 共有しておきたいニュース

- Google から Gemini CLI がリリース。Claude Code のような CLI ベースの AI エージェント。コーディングは、Claude Code の方が優れているという評価をよく見かけますが、画像生成などもできるようなので、コーディング以外の用途で使える場面も多そうです。
- Claude Code が、 Pro プランでも利用できるようになりました。
- Claude Code に Hook 機能がつきました。応答やツールの利用の前後などでコマンドを実行できるようになったようです。
- Cursor から Ultra プランがリリースされました。使い放題になりましたが、Claude Code 使ってる人が多い印象です。
- Cursor がブラウザから操作できるようになりました。

## 最近の流れ

- AI エージェントガチ勢の間では、Claude Code が引き続き一番人気に感じます。
- ターミナルを大量(6 枚とか 9 枚とか)に開いて、連携させて使っている人がいますが、デモ的には派手なものの、あまり実用性は感じない。
- AI 搭載ブラウザがちょこちょこ出てきています。
- まだ流行ってはいないけど、コンテナ内で AI を使う流れは来そう。AI に好き勝手させる際のリスクがある程度軽減できる。
- Google Cloud Vertex AI や AWS Bedrock など、経由で LLM を使う流れは、大企業が LLM やコーディングエージェントを使う際には必要になってくるので押さえておくとよいかも。
- AI コーディングをする上で、コンテキストエンジニアリングが重要になるかも(急に出てきた)

## 押さえておきたい話

- [Andrej Karpathy: Software Is Changing](./ai-scrapbook45-20250708-Andrej-Karpathy-Software-Is-Changing.md)

---

### [AI に「分からない」と言わせるための「RAG」の手法](https://zenn.dev/knowledgesense/articles/468d7c853901f8)

![AIに「分からない」と言わせるための「RAG」の手法](https://res.cloudinary.com/zenn/image/upload/s--ewBIJuL3--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:AI%25E3%2581%25AB%25E3%2580%258C%25E5%2588%2586%25E3%2581%258B%25E3%2582%2589%25E3%2581%25AA%25E3%2581%2584%25E3%2580%258D%25E3%2581%25A8%25E8%25A8%2580%25E3%2582%258F%25E3%2581%259B%25E3%2582%258B%25E3%2581%259F%25E3%2582%2581%25E3%2581%25AE%25E3%2580%258CRAG%25E3%2580%258D%25E3%2581%25AE%25E6%2589%258B%25E6%25B3%2595%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Atsushi%2520Kadowaki%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly96ZW5uLmRldi9pbWFnZXMvZGVmYXVsdC1wdWJsaWNhdGlvbi1hdmF0YXIucG5n%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E3%2583%258A%25E3%2583%25AC%25E3%2583%2583%25E3%2582%25B8%25E3%2582%25BB%25E3%2583%25B3%25E3%2582%25B9%2520-%2520AI%25E7%259F%25A5%25E8%25A6%258B%25E5%2585%25B1%25E6%259C%2589%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzRlMjk5Y2IwN2IuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [MCP Client を活用するための設計と実装上の工夫](https://speakerdeck.com/yudai00/mcp-clientwohuo-yong-surutamenoshe-ji-toshi-zhuang-shang-nogong-fu)

![MCP Clientを活用するための設計と実装上の工夫](https://files.speakerdeck.com/presentations/09960b4ef9a8469aa2ef4bb6a2f4aa07/slide_0.jpg?35315104)

MCPOps LT 大会で発表した内容になります
connpass: https://mlops.connpass.com/event/352150/

---

### [Cloud Run GPU の概要｜ npaka](https://note.com/npaka/n/n6b26d1e47325)

![Cloud Run GPU の概要｜npaka](https://assets.st-note.com/production/uploads/images/193855341/rectangle_large_type_2_5ccb7761184afe51137b03f75179e34e.png?fit=bounds&quality=85&width=1280)

以下の記事が面白かったので、簡単にまとめました。 ・Cloud Run GPUs, now GA, makes running AI workloads easier for everyone 1. Cloud Run GPU 「Cloud Run」は、「Google Cloud」のサーバレスランタイムです。本日 (2025 年 6 月 3 日)、「Cloud Run」における「NVIDIA GPU」サポートの一般提供が開始されました。これにより、様々なユースケースに対応するパワフルなランタイムが実現し、コスト効率も非常に優れています。 GPU と CPU の両方で、以下のメリットを享受

---

### [TypeScript 環境構築ガイドラインを書いて LLM に再現させる](https://zenn.dev/mizchi/articles/llm-aware-ts-project-starter)

![TypeScript 環境構築ガイドラインを書いてLLMに再現させる](https://res.cloudinary.com/zenn/image/upload/s--8HxWzAhX--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:TypeScript%2520%25E7%2592%25B0%25E5%25A2%2583%25E6%25A7%258B%25E7%25AF%2589%25E3%2582%25AC%25E3%2582%25A4%25E3%2583%2589%25E3%2583%25A9%25E3%2582%25A4%25E3%2583%25B3%25E3%2582%2592%25E6%259B%25B8%25E3%2581%2584%25E3%2581%25A6LLM%25E3%2581%25AB%25E5%2586%258D%25E7%258F%25BE%25E3%2581%2595%25E3%2581%259B%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:mizchi%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2liclRHT052Z3d3ay1fNGxlcVk4TGNGSlNuX0FoWnpEWVlKaXJNcWc9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [社内で AI 駆動開発ツールの使用調査したら、たった 1 週間で『Claude Code』一択になっていた話](https://zenn.dev/explaza/articles/f62e704e73d3ff)

![社内でAI駆動開発ツールの使用調査したら、たった1週間で『Claude Code』一択になっていた話](https://res.cloudinary.com/zenn/image/upload/s--P5f2fz82--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E7%25A4%25BE%25E5%2586%2585%25E3%2581%25A7AI%25E9%25A7%2586%25E5%258B%2595%25E9%2596%258B%25E7%2599%25BA%25E3%2583%2584%25E3%2583%25BC%25E3%2583%25AB%25E3%2581%25AE%25E4%25BD%25BF%25E7%2594%25A8%25E8%25AA%25BF%25E6%259F%25BB%25E3%2581%2597%25E3%2581%259F%25E3%2582%2589%25E3%2580%2581%25E3%2581%259F%25E3%2581%25A3%25E3%2581%259F1%25E9%2580%25B1%25E9%2596%2593%25E3%2581%25A7%25E3%2580%258EClaude%2520Code%25E3%2580%258F%25E4%25B8%2580%25E6%258A%259E%25E3%2581%25AB%25E3%2581%25AA%25E3%2581%25A3%25E3%2581%25A6%25E3%2581%2584%25E3%2581%259F%25E8%25A9%25B1%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:%25E3%2582%25A6%25E3%2583%25B3%25E3%2582%25B9%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2Y1YTdhNDEwNjYuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E6%25A0%25AA%25E5%25BC%258F%25E4%25BC%259A%25E7%25A4%25BE%25E3%2582%25A8%25E3%2582%25AF%25E3%2582%25B9%25E3%2583%2597%25E3%2583%25A9%25E3%2582%25B6%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzVlZmYzMTA2MDQuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code を徹底解説してみた（前編） | DevelopersIO](https://dev.classmethod.jp/articles/get-started-claude-code-1/)

![Claude Codeを徹底解説してみた（前編） | DevelopersIO](https://images.ctfassets.net/ct0aopd36mqt/wp-thumbnail-75c24212db08a605cf51b1578f9a040c/f14b12b1b1cf9b5ed2427490ff86734d/eyecatch_anthropic)

---

### [X ユーザーのまさお@AI 駆動開発さん: 「🚨 ClaudeCode の便利ツール発見！！ これ見やすくて良さそう 👀 ✔️ClaudeCode との会話ログを読みやすいページにしてくれる ✔️ プロジェクトごとに回遊できる ✔️ 無料で気軽にやれる これは嬉しい人多いのでは 🙏 https://t.co/IByVFVBdNg」 / X](https://x.com/AI_masaou/status/1934625256179974400)

![Xユーザーのまさお@AI駆動開発さん: 「🚨 ClaudeCodeの便利ツール発見！！ これ見やすくて良さそう👀  ✔️ClaudeCodeとの会話ログを読みやすいページにしてくれる ✔️プロジェクトごとに回遊できる ✔️無料で気軽にやれる  これは嬉しい人多いのでは🙏 https://t.co/IByVFVBdNg」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの a null-sensei さん: 「あとでよむ Claude Code と GitHub Issue を使った全自動開発について | 📓 memotty https://t.co/p9ZQaalRC1」 / X](https://x.com/GOROman/status/1934796352292311485)

![Xユーザーのa null-senseiさん: 「あとでよむ  Claude CodeとGitHub Issueを使った全自動開発について | 📓 memotty https://t.co/p9ZQaalRC1」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの田中義弘 | taziku CEO / AI × Creative さん: 「画像 1 枚 → 部品ごとに分かれた 3D モデルに自動変換。 NVIDIA の PartPacker が凄い。1 枚の 2D 画像から“意味ある構造ごとの 3D パーツ”を生成し、形状もきれいに保ったまま編集可能。 3D モデリングの革命かもしれない。デモなどは 🧵 から https://t.co/EM79Ju23yF」 / X](https://x.com/taziku_co/status/1934754138459664576)

![Xユーザーの田中義弘 | taziku CEO / AI × Creativeさん: 「画像1枚 → 部品ごとに分かれた3Dモデルに自動変換。  NVIDIAのPartPackerが凄い。1枚の2D画像から“意味ある構造ごとの3Dパーツ”を生成し、形状もきれいに保ったまま編集可能。  3Dモデリングの革命かもしれない。デモなどは🧵から https://t.co/EM79Ju23yF」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーのカッコ 🌈10/25 和気あい AI4 さん: 「にじじゃーにーの動画モデル先行体験させていただきました！！！！！！見て！！！！かわいい！！！ #nijijourney #Niji\_動画モデル先行体験 https://t.co/WAgygMi3Rh」 / X](https://x.com/kakowara24/status/1934734296293757167)

![Xユーザーのカッコ🌈10/25和気あいAI4さん: 「にじじゃーにーの動画モデル先行体験させていただきました！！！！！！見て！！！！かわいい！！！ #nijijourney #Niji_動画モデル先行体験 https://t.co/WAgygMi3Rh」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの erukiti さん: 「https://t.co/foPA4uvFQz 「バイブコーディング提唱者の“仕事”の仕方はこうだ」はちょうど Claude Code（定額使い放題）と相性がいい &gt; ３）案を選んで、コードのたたき台をもらう &gt; ・「このやり方でいこう」と 1 つ選んで、最初のコードを AI に書かせる。」 / X](https://x.com/erukiti/status/1934761303329169706)

![Xユーザーのerukitiさん: 「https://t.co/foPA4uvFQz  「バイブコーディング提唱者の“仕事”の仕方はこうだ」はちょうどClaude Code（定額使い放題）と相性がいい  > ３）案を選んで、コードのたたき台をもらう > ・「このやり方でいこう」と1つ選んで、最初のコードをAIに書かせる。」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの神威/KAMUI さん: 「お〜 Hunyuan3d の v2.1 マットな質感が表現できていて良いね 💡 #kamuiart https://t.co/ecU9tF10lz」 / X](https://x.com/kamui_qai/status/1934661991857311776)

![Xユーザーの神威/KAMUIさん: 「お〜 Hunyuan3dのv2.1  マットな質感が表現できていて良いね💡  #kamuiart https://t.co/ecU9tF10lz」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [簡単な MCP サーバ を作って Cloud Run へのデプロイを試す｜ npaka](https://note.com/npaka/n/n9083d9f385cd?sub_rt=share_pw)

![簡単なMCPサーバ を作って Cloud Run へのデプロイを試す｜npaka](https://assets.st-note.com/production/uploads/images/196469273/rectangle_large_type_2_ceccdf87463e013e5518140bf942b6e4.png?fit=bounds&quality=85&width=1280)

簡単な MCP サーバ を作って「Cloud Run」にデプロイを試したのでまとめました。 前回

1.  簡単な MCP サーバの作成 簡単な MCP サーバ (mcp-server-sample) を作成します。持ってるツールは加算(add)のみです。 (1) プロジェクトの作成。 uv をインストールしておく必要があります。 mkdir helloworld
    cd helloworld
    uv init
    uv add fastmcp (2) 「server.py」の追加。 ・server.py import asyncio
    import os
    from fastmcp impor

---

### [Claude Code の会話ログを DuckDB で分析して自分の仕事スタイルを改善する方法 - yasuhisa's blog](https://www.yasuhisay.info/entry/2025/06/15/162704)

![Claude Codeの会話ログをDuckDBで分析して自分の仕事スタイルを改善する方法 - yasuhisa's blog](https://ogimage.blog.st-hatena.com/12704591929890344785/6802418398475503564/1750195604)

3 行まとめ はじめに Claude Code のログ保存機能とその特徴 ログ分析の活用例 音声入力の課題と英語プロンプトの活用 DuckDB を用いた分析アプローチ スキーマ情報の重要性とログ分析の活用 ログの長期保存設定 まとめ 3 行まとめ Claude Code の会話ログは JSONL 形式で保存されており、DuckDB を使って日次の利用状況や音声入力の課題などを分析できる 英語プロンプトの学習効率化やエラーパターンの特定など、自分の仕事の仕方を改善するための実践的な活用方法がある JSONL ファイルのスキーマ情報を整理することで、Claude Code がクエリを書く際の精度が向上する はじめに …

---

### [AI とどう付き合っていくか 2025 春](https://zenn.dev/nekoruri/articles/living-with-ai-2025-spring)

![AIとどう付き合っていくか 2025春](https://res.cloudinary.com/zenn/image/upload/s--Gv9y5qwS--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:AI%25E3%2581%25A8%25E3%2581%25A9%25E3%2581%2586%25E4%25BB%2598%25E3%2581%258D%25E5%2590%2588%25E3%2581%25A3%25E3%2581%25A6%25E3%2581%2584%25E3%2581%258F%25E3%2581%258B%25202025%25E6%2598%25A5%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:nekoruri%2520%257C%2520%25E3%2582%2581%25E3%2582%2582%25E3%2581%258A%25E3%2581%258D%25E3%2581%25B0%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2hNU3hvYm1YeHlfNTR5SFBlOXIwcU1tTnlOWWtzZ0FmZzZpN3BIZUE9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [ビジネス向けガイドとリソース](https://openai.com/ja-JP/business/guides-and-resources/)

![ビジネス向けガイドとリソース](https://images.ctfassets.net/kftzwdyauwt9/3KGOHkSXu53naMuSFNaiwv/aa2f914943c839ce6b75b8620a46b340/SEO_Banner_2560x1440_02.png?w=1600&h=900&fit=fill)

OpenAI の専門家主導のコンテンツライブラリをご覧ください。スタートアップ企業、エンタープライズ企業、開発者が AI 導入を加速させるための詳細なリソースを見つけることができます。

---

### [Claude Code 完全攻略 Wiki(隠しコマンド編 - think,拡張機能,思考予算)](https://zenn.dev/fbbp/articles/7aa9a46518a609)

![Claude Code完全攻略Wiki(隠しコマンド編 - think,拡張機能,思考予算)](https://res.cloudinary.com/zenn/image/upload/s--xqL8v3Vx--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E5%25AE%258C%25E5%2585%25A8%25E6%2594%25BB%25E7%2595%25A5Wiki%2528%25E9%259A%25A0%25E3%2581%2597%25E3%2582%25B3%25E3%2583%259E%25E3%2583%25B3%25E3%2583%2589%25E7%25B7%25A8%2520-%2520think%252C%25E6%258B%25A1%25E5%25BC%25B5%25E6%25A9%259F%25E8%2583%25BD%252C%25E6%2580%259D%25E8%2580%2583%25E4%25BA%2588%25E7%25AE%2597%2529%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:fbbp%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUNnOG9jSWdDZkJfU2dPc1FxMkZwYnZmWWM5N3QyQ3R0UzBVMC1lWXNLOTR1Zk5ZZXc9czk2LWM=%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [A2A プロトコルの JavaScript SDK を試してみる](https://azukiazusa.dev/blog/a2a-protocol-js-sdk/)

![A2A プロトコルの JavaScript SDK を試してみる](https://azukiazusa.dev/blog/ogp/a2a-protocol-js-sdk.png)

A2A プロトコルはエージェント間の通信を標準化するためのプロトコルです。JavaScript SDK を使って A2A サーバーとクライアントを実装し、エージェント間通信を試してみます。

---

### [[2025 年 6 月 13 日] やっぱり Claude Code しか勝たんかもしれない (週刊 AI)](https://zenn.dev/carenet/articles/59f62014092a1b)

![[2025年6月13日] やっぱりClaude Codeしか勝たんかもしれない (週刊AI)](https://res.cloudinary.com/zenn/image/upload/s--n2SbrDTj--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%255B2025%25E5%25B9%25B46%25E6%259C%258813%25E6%2597%25A5%255D%2520%25E3%2582%2584%25E3%2581%25A3%25E3%2581%25B1%25E3%2582%258AClaude%2520Code%25E3%2581%2597%25E3%2581%258B%25E5%258B%259D%25E3%2581%259F%25E3%2582%2593%25E3%2581%258B%25E3%2582%2582%25E3%2581%2597%25E3%2582%258C%25E3%2581%25AA%25E3%2581%2584%2520%2528%25E9%2580%25B1%25E5%2588%258AAI%2529%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Kai%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzE0MTRiZmIwZWQuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:CareNet%2520Engineers%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUVkRlRwN0luX0J2ajYyMjVsbTRVWXczSjhQODgwRTdhSFF6YXZqcmJHN1E9czk2LWM=%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code の問題解決能力の底上げを試みる：MCP サーバー + subagents](https://zenn.dev/oikon/articles/82c9a52dc45810)

![Claude Codeの問題解決能力の底上げを試みる：MCPサーバー + subagents](https://res.cloudinary.com/zenn/image/upload/s--cJdC36AG--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AE%25E5%2595%258F%25E9%25A1%258C%25E8%25A7%25A3%25E6%25B1%25BA%25E8%2583%25BD%25E5%258A%259B%25E3%2581%25AE%25E5%25BA%2595%25E4%25B8%258A%25E3%2581%2592%25E3%2582%2592%25E8%25A9%25A6%25E3%2581%25BF%25E3%2582%258B%25EF%25BC%259AMCP%25E3%2582%25B5%25E3%2583%25BC%25E3%2583%2590%25E3%2583%25BC%2520%252B%2520subagents%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Oikon%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzFlNjI2MjNlZTQuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーのせせり｜個人 web 開発者さん: 「これはここだけの話なんですが、Windows の人は「棒読みちゃん」を立ち上げておくと TCP でメッセージを投げるだけで喋ってくれるので、これを組んでおくと Claude Code が作業報告を音声読み上げしてくれるので色々捗ります https://t.co/l7MzPpafsT」 / X](https://x.com/sesere115/status/1933935174192140561)

![Xユーザーのせせり｜個人web開発者さん: 「これはここだけの話なんですが、Windowsの人は「棒読みちゃん」を立ち上げておくとTCPでメッセージを投げるだけで喋ってくれるので、これを組んでおくとClaude Codeが作業報告を音声読み上げしてくれるので色々捗ります https://t.co/l7MzPpafsT」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの gura さん: 「読んだ タスクの動的度の高い AI エージェント(Plan-Executor, ReAct 系)は実行 ➔ 評価 ➔ 改善のループ自体を LLM 使って自動化するのがマストだという再確認 そのために必要なのがサンドボックス環境と LLM as judge, AI コーディングの 3 点セットかな https://t.co/tGl3mdw6Ja」 / X](https://x.com/gura105/status/1933990454812696893)

![Xユーザーのguraさん: 「読んだ  タスクの動的度の高いAIエージェント(Plan-Executor, ReAct系)は実行➔評価➔改善のループ自体をLLM使って自動化するのがマストだという再確認  そのために必要なのがサンドボックス環境とLLM as judge, AIコーディングの3点セットかな  https://t.co/tGl3mdw6Ja」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの Kazunori Sato さん: 「AI ＋形式手法＋関数型、面白い。 https://t.co/Kn0nKOJKRr https://t.co/FYtmrGxe3H」 / X](https://x.com/kazunori_279/status/1934011522034106392)

![XユーザーのKazunori Satoさん: 「AI＋形式手法＋関数型、面白い。 https://t.co/Kn0nKOJKRr https://t.co/FYtmrGxe3H」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーのまさお@AI 駆動開発さん: 「🚨 これ絶対抑えておいてください。神記事。 ✅ClaudeCode には subagent という機能が標準搭載 ① use subagent や multiple subagent と呼び出して利用可 ② ユーザーが触れてる親 agent のコンテキストを消費しない=より精度よく走り続けられる ③ スラッシュコマンドでこの設定をすると便利 https://t.co/7Nui6glqQG」 / X](https://x.com/AI_masaou/status/1933776281218502926)

![Xユーザーのまさお@AI駆動開発さん: 「🚨これ絶対抑えておいてください。神記事。  ✅ClaudeCodeにはsubagentという機能が標準搭載  ① use subagentやmultiple subagentと呼び出して利用可  ② ユーザーが触れてる親agentのコンテキストを消費しない=より精度よく走り続けられる  ③ スラッシュコマンドでこの設定をすると便利 https://t.co/7Nui6glqQG」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [バイブコーディングチュートリアル：Claude Code でカンバンアプリケーションを作成しよう](https://azukiazusa.dev/blog/vibe-coding-tutorial-create-app-with-claude-code/)

![バイブコーディングチュートリアル：Claude Code でカンバンアプリケーションを作成しよう](https://azukiazusa.dev/blog/ogp/vibe-coding-tutorial-create-app-with-claude-code.png)

バイブコーディングとは、AI エージェントを活用して直感的にアプリケーションを開発する新しいコーディングスタイルです。このチュートリアルでは、Claude Code を使って Next.js でカンバンボードアプリケーションを作成します。

---

### [X ユーザーのまさお@AI 駆動開発さん: 「🚨 これ使ってない人、仕事遅いです 無料プランでも使えるので、今すぐ使いましょう 実は RaycastAI が API キーでの AI 機能の利用を解放しています 動画のように、選択部を瞬間的に AI で書き換える/質問などがすぐにできます MCP を簡単導入の AI Chat 機能もとても便利 モデル選択も自由！最高です！！ https://t.co/YBMRNccJeY」 / X](https://x.com/AI_masaou/status/1933815714907042034)

![Xユーザーのまさお@AI駆動開発さん: 「🚨 これ使ってない人、仕事遅いです 無料プランでも使えるので、今すぐ使いましょう  実はRaycastAIがAPIキーでのAI機能の利用を解放しています 動画のように、選択部を瞬間的にAIで書き換える/質問などがすぐにできます  MCPを簡単導入のAI Chat機能もとても便利  モデル選択も自由！最高です！！ https://t.co/YBMRNccJeY」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Claude Max プラン料金内で Claude Code GitHub Actions を使うためのガイドまとめ - Qiita](https://qiita.com/akira_papa_AI/items/e101a4e3ac9844e7b313)

![Claude Maxプラン料金内でClaude Code GitHub Actionsを使うためのガイドまとめ - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Farticle-ogp-background-afbab5eb44e0b055cce1258705637a91.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1pbWFnZS1zdG9yZSUyRjAlMkY0MzUyMzMlMkYzYWVhMjJjODY0NGRjN2RhNzNhYmNiZWViNzNiMzQ5NTY1ZjFhYzg3JTJGeF9sYXJnZS5wbmclM0YxNzQzODkzNzQwP2l4bGliPXJiLTQuMC4wJmFyPTElM0ExJmZpdD1jcm9wJm1hc2s9ZWxsaXBzZSZiZz1GRkZGRkYmZm09cG5nMzImcz0zYzAxZGY0NTQwNDA3MDkxOWU4ZDc1YjJmMGMwODg1MQ%26blend-x%3D120%26blend-y%3D467%26blend-w%3D82%26blend-h%3D82%26blend-mode%3Dnormal%26s%3D57d66a48ec5d58fdc4e5256f39ac787a?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9Q2xhdWRlJTIwTWF4JUUzJTgzJTk3JUUzJTgzJUE5JUUzJTgzJUIzJUU2JTk2JTk5JUU5JTg3JTkxJUU1JTg2JTg1JUUzJTgxJUE3Q2xhdWRlJTIwQ29kZSUyMEdpdEh1YiUyMEFjdGlvbnMlRTMlODIlOTIlRTQlQkQlQkYlRTMlODElODYlRTMlODElOUYlRTMlODIlODElRTMlODElQUUlRTMlODIlQUMlRTMlODIlQTQlRTMlODMlODklRTMlODElQkUlRTMlODElQTglRTMlODIlODEmdHh0LWFsaWduPWxlZnQlMkN0b3AmdHh0LWNvbG9yPSUyMzFFMjEyMSZ0eHQtZm9udD1IaXJhZ2lubyUyMFNhbnMlMjBXNiZ0eHQtc2l6ZT01NiZ0eHQtcGFkPTAmcz00N2RhM2Q4YWIyZmU4NWExM2RmY2NmOGZjYTg0ZjNhMA&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDBha2lyYV9wYXBhX0FJJnR4dC1jb2xvcj0lMjMxRTIxMjEmdHh0LWZvbnQ9SGlyYWdpbm8lMjBTYW5zJTIwVzYmdHh0LXNpemU9MzYmdHh0LXBhZD0wJnM9Njg4MDRmOGExYzc3N2U4YTc5ZDg2NzcxYzljNzViN2U&blend-x=242&blend-y=480&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&s=28e0e75c60b0dcf237319e1e651ecb2b)

📋 必要なもの Claude Max サブスクリプション（月額 200） GitHub アカウント（リポジトリの管理者権限必須） Claude Code がローカルにインストール済み 🔧 事前準備：リポジトリのフォーク フォークが必要なリポジトリ ...

---

### [Claude Code による技術的特異点を見届けろ](https://zenn.dev/mizchi/articles/claude-code-singularity-point)

![Claude Code による技術的特異点を見届けろ](https://res.cloudinary.com/zenn/image/upload/s--0gY0jgcX--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%2520%25E3%2581%25AB%25E3%2582%2588%25E3%2582%258B%25E6%258A%2580%25E8%25A1%2593%25E7%259A%2584%25E7%2589%25B9%25E7%2595%25B0%25E7%2582%25B9%25E3%2582%2592%25E8%25A6%258B%25E5%25B1%258A%25E3%2581%2591%25E3%2582%258D%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:mizchi%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2liclRHT052Z3d3ay1fNGxlcVk4TGNGSlNuX0FoWnpEWVlKaXJNcWc9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Mastra Cloud を使って AI エージェントを簡単にデプロイしよう｜ニケちゃん](https://note.com/nike_cha_n/n/nc2c56e3c8fd1?sub_rt=share_pb)

![Mastra Cloudを使ってAIエージェントを簡単にデプロイしよう｜ニケちゃん](https://assets.st-note.com/production/uploads/images/195763054/rectangle_large_type_2_f474f4ded516905dd38ce113a142b481.png?fit=bounds&quality=85&width=1280)

こんにちは、ニケです。 皆さん、Mastra&nbsp;使っていますでしょうか？ 手軽に作れる AI エージェントフレームワークとして、最近また話題に上がってきている気がしますね。 私も過去に何回か記事にしています。

今回は Mastra で作った AI エージェントを Mastra Cloud でデプロイする方法について紹介します。 今回使用するアプリはこちらにあります。 Mastra とは Mastra（マストラ）は、AI エージェント開発を効率化するためのオープンソースフレームワークです。 TypeScript で実装されており、LLM を利用して外部 API やツールを呼び出す

---

### [X ユーザーのしば田 | Programming x AI さん: 「「マルチエージェントを作るな」を読んだ。 釣りっぽいタイトルだけど内容は至極真っ当で、どちらかというと「並列稼働に気をつけろ」みたいな内容だった。」 / X](https://x.com/KeisukeShibata_/status/1933338979358904724)

![Xユーザーのしば田 | Programming x AIさん: 「「マルチエージェントを作るな」を読んだ。  釣りっぽいタイトルだけど内容は至極真っ当で、どちらかというと「並列稼働に気をつけろ」みたいな内容だった。」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [AI コーディング新時代を生き残るための試行錯誤 / AI Coding Survival Guide](https://speakerdeck.com/tomohisa/ai-coding-survival-guide)

![AIコーディング新時代を生き残るための試行錯誤 / AI Coding Survival Guide](https://files.speakerdeck.com/presentations/11a8733e5f5444aeab9bface03083fd4/slide_0.jpg?35434380)

https://layerx.connpass.com/event/355449/
AI Coding Meetup #2 Cline/RooCode/Claude Code の活用事例
「AI Coding × チーム開発 × 組織での実践」にフォーカスを当てるイベント、での登壇です。

株式会&hellip;

---

### [Roo Code と Claude Code 比較してみた](https://speakerdeck.com/pharma_x_tech/roo-codetoclaude-codebi-jiao-sitemita)

![Roo CodeとClaude Code比較してみた](https://files.speakerdeck.com/presentations/3aa8f59a2123401ca23efe3ff632efdc/slide_0.jpg?35436044)

---

### [僕が Claude Code に食われた日 - Stockmark Tech Blog](https://stockmark-tech.hatenablog.com/entry/2025/06/12/091850)

![僕がClaude Codeに食われた日 - Stockmark Tech Blog](https://ogimage.blog.st-hatena.com/6801883189091729073/6802418398468917887/1749687548)

こんにちは。 Anews の開発に携わっている Engineer の 羽柴 と申します。 先週 Claude Code を使い始めて衝撃を受け、勢いそのままに社内に布教活動をしました。 という内容を SNS にシェアしたら思ったより反響が テンション上がりすぎて社内向けに書いた pic.twitter.com/as6qVwsWUX— hashiba ｜ software_engineer (@baan_nasebanaru) 2025 年 6 月 6 日 上記の notion は感情に任せた内容なので、この記事は少し落ち着いて書き直した内容です。 なぜ生成 AI を開発に組み込むのか？ 社内に共有されている考え方 …

---

### [X ユーザーの korinVR（こりん）さん: 「わーい、Windows の WSL の Claude Code から Unity のコンパイルをトリガーしてエラーログ取得して自動的に直すやつができた。もっといい方法あるかもだけど https://t.co/jlHRagEOmV」 / X](https://x.com/korinVR/status/1933138433146519678)

![XユーザーのkorinVR（こりん）さん: 「わーい、WindowsのWSLのClaude CodeからUnityのコンパイルをトリガーしてエラーログ取得して自動的に直すやつができた。もっといい方法あるかもだけど https://t.co/jlHRagEOmV」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [AI アシスタント「あざらしすたんと」 | ProtoPedia](https://protopedia.net/prototype/6212)

![AIアシスタント「あざらしすたんと」 | ProtoPedia](https://protopedia.net/pic/b505e04b-18a3-4ca8-ab75-a7474cf4af81.png)

話かけるだけで、AI アザラシ「らしたん」がドキュメントをまとめてくれたり、チャットを盛り上げたりと日々の仕事を効率的で楽しいものにしてくれます。mac 上のできることは全て らしたん にお任せ！

---

### [X ユーザーのこぎそさん: 「v0 から生成した UI を直接編集できる機能が出たか 👀 いよいよデザインツールを介さずとも作れる世界線の解像度が上がってきた。」 / X](https://x.com/kgsi/status/1932956387367383121)

![Xユーザーのこぎそさん: 「v0から生成したUIを直接編集できる機能が出たか👀 いよいよデザインツールを介さずとも作れる世界線の解像度が上がってきた。」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [AI 領域における組織の強みを活かすアーキテクチャ設計](https://zenn.dev/aishift/articles/c897d0e095c3d8)

![AI領域における組織の強みを活かすアーキテクチャ設計](https://res.cloudinary.com/zenn/image/upload/s--Lj4mPYnC--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:AI%25E9%25A0%2598%25E5%259F%259F%25E3%2581%25AB%25E3%2581%258A%25E3%2581%2591%25E3%2582%258B%25E7%25B5%2584%25E7%25B9%2594%25E3%2581%25AE%25E5%25BC%25B7%25E3%2581%25BF%25E3%2582%2592%25E6%25B4%25BB%25E3%2581%258B%25E3%2581%2599%25E3%2582%25A2%25E3%2583%25BC%25E3%2582%25AD%25E3%2583%2586%25E3%2582%25AF%25E3%2583%2581%25E3%2583%25A3%25E8%25A8%25AD%25E8%25A8%2588%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:ytaisei%25EF%25BC%2588%25E3%2581%259F%25E3%2581%2584%25E3%2581%259B%25E3%2583%25BC%25EF%25BC%2589%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzhhNDQwNmNlMGUuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:AI%2520Shift%2520Tech%2520Blog%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzZmNTZlNDI3NWQuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーのまさお@AI 駆動開発さん: 「🚨 Genspark からリリースされた AI ブラウザがヤバすぎた 今回ブラウザと同時に MCP マーケットプレイスも公開されたが 標準でインストールされている MCP(ツール)には、"ブラウザ"であることをフルに活かした X や Reddit の検索ツールや、ローカルツールが！ そう来たかと納得した https://t.co/xofNLNOTDV」 / X](https://x.com/AI_masaou/status/1932789806599446815)

![Xユーザーのまさお@AI駆動開発さん: 「🚨 GensparkからリリースされたAIブラウザがヤバすぎた  今回ブラウザと同時にMCPマーケットプレイスも公開されたが  標準でインストールされているMCP(ツール)には、"ブラウザ"であることをフルに活かしたXやRedditの検索ツールや、ローカルツールが！  そう来たかと納得した https://t.co/xofNLNOTDV」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Claude Code で内部統制３点セットを作る（Drawio フロー図の生成）｜兎耳山ルカ 公認会計士](https://note.com/tomiyamaluca/n/n19614916cc5a)

![Claude Codeで内部統制３点セットを作る（Drawioフロー図の生成）｜兎耳山ルカ 公認会計士](https://assets.st-note.com/production/uploads/images/195401842/rectangle_large_type_2_cae57719bb273e19e21fa7bd7eadd160.png?fit=bounds&quality=85&width=1280)

Claude Code はビジネス文書に広く活用できる！

              AIはこれが一発で出る時代になりました Drawioでここから自在に加工できます pic.twitter.com/sm7e5tDkpt — 兎耳山ルカ 公認会計士 (@TomiyamaLuca) June 8, 2025

Claude code で Draw.io を用いた業務フロー図を作成したよ、というツイートをしたところ沢山の関心のお声をいただいたので、共有できるリポジトリを作成しました。 GitHub リポ 「CC_Inter

---

### [X ユーザーのあきらパパ【生成 AI 活用エンジニア&３児のパパ】さん: 「ちなみに gemma-3-12b は速いし賢かったです〜☺️ ローカル LLM でこのスピード出るのすごいし、簡単な作業タスクならこの gemma で十分そうだ 🙌☺️ これは無料てなかなかやばい凄いっすね Google さん 🎵 https://t.co/IsxwMFUAs7」 / X](https://x.com/akira_papa_IT/status/1932560997149250008)

![Xユーザーのあきらパパ【生成AI活用エンジニア&３児のパパ】さん: 「ちなみにgemma-3-12bは速いし賢かったです〜☺️ ローカルLLMでこのスピード出るのすごいし、簡単な作業タスクならこのgemmaで十分そうだ🙌☺️ これは無料てなかなかやばい凄いっすねGoogleさん🎵 https://t.co/IsxwMFUAs7」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーのテツメモ｜ AI 図解 × 検証｜ Newsletter さん: 「📝 YAML 式プロンプトのお試しありがとうございます！ 要素が細かく分類されているので微調整が楽 - 自分で手直ししても OK - AI に修正してもらうのも OK YAML× 画像生成は AI を楽しむ良いキッカケになります！ 「ビジネスモデルや概念図」もポン出しできる 他のプロンプトもリプ欄で紹介　 👇 https://t.co/sixl94uTM2」 / X](https://x.com/tetumemo/status/1932364324779250025)

![Xユーザーのテツメモ｜AI図解×検証｜Newsletterさん: 「📝 YAML式プロンプトのお試しありがとうございます！  要素が細かく分類されているので微調整が楽  - 自分で手直ししてもOK - AIに修正してもらうのもOK  YAML×画像生成はAIを楽しむ良いキッカケになります！  「ビジネスモデルや概念図」もポン出しできる  他のプロンプトもリプ欄で紹介　👇 https://t.co/sixl94uTM2」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーのあきらパパ【生成 AI 活用エンジニア&３児のパパ】さん: 「Macbook M4 Max メモリ 64GB でローカル LLM 動かす便利ツール「LM Studio」を使って Qwen3-235b-a22b の 100GB 越えの LLM 入れて動かしてみたらこのスピードでした 👀 ３秒１文字くらいかな、動かせたらかなり賢い代物だけど、ちょっと mac じゃ厳しそうでしたレビューシェア ☺️🙌 LM Studio - Discover, https://t.co/8iYcaJyxkM」 / X](https://x.com/akira_papa_IT/status/1932560218241843232)

![Xユーザーのあきらパパ【生成AI活用エンジニア&３児のパパ】さん: 「Macbook M4 Max メモリ64GBでローカルLLM動かす便利ツール「LM Studio」を使って Qwen3-235b-a22bの100GB越えのLLM入れて動かしてみたらこのスピードでした👀  ３秒１文字くらいかな、動かせたらかなり賢い代物だけど、ちょっとmacじゃ厳しそうでしたレビューシェア☺️🙌  LM Studio - Discover, https://t.co/8iYcaJyxkM」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの ChatGPT 研究所さん: 「【必見】サム・アルトマンのみている世界 パート 2 OpenAI CEO のサム・アルトマンが、『穏やかなシンギュラリティ（The Gentle Singularity）』と題した長文ブログを投稿しました。これは見逃せない内容だと思い、全文翻訳を作成しました 👇 # 穏やかなシンギュラリティ 6 月 11 日 https://t.co/eK8ppv2eLT」 / X](https://x.com/ctgptlb/status/1932591333879001579)

![XユーザーのChatGPT研究所さん: 「【必見】サム・アルトマンのみている世界 パート2  OpenAI CEO のサム・アルトマンが、『穏やかなシンギュラリティ（The Gentle Singularity）』と題した長文ブログを投稿しました。これは見逃せない内容だと思い、全文翻訳を作成しました👇  # 穏やかなシンギュラリティ 6月11日 https://t.co/eK8ppv2eLT」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [【AI 開発時代】Claude Code 学び直しノート - 15 分で時代に追いつけるか？ - uepon 日々の備忘録](https://uepon.hatenadiary.com/entry/2025/06/10/134022)

![【AI開発時代】Claude Code学び直しノート - 15分で時代に追いつけるか？ - uepon日々の備忘録](https://ogimage.blog.st-hatena.com/8454420450106035947/6802418398461887193/1749530422)

スマヌ 15 分では追いつけなかったよ…トラブルに引っかかったので 60 分かかった 😢😢😢 ※Node.js のインストールトラブルがなければ 15 分で終わるでしょう。 かなり無理を言ってる 🤔 わかってるでもやらないと追いつけない…😫 という話となります。さて短時間で学び直しはできるのでしょうか。 【スペック】 半世紀生きたジジイ 👴 業務開発経験は基本無い（副業レベル） Ubuntu と Python はそれなりに分かる ⌨️ Node.js は初心者レベル Windows 派 🪟 開発は WSL か Docker🐳 Claude Code って何？ ターミナル上で動く AI コーディングアシスタントです。プロンプトに「〜を作って」…

---

### [X ユーザーのあきらパパ【生成 AI 活用エンジニア&３児のパパ】さん: 「【tmux で Claude Code の Max プランで AI 組織を動かし放題のローカル環境ができた〜〜〜！！！🔥🔥🔥🙌☺️】 ダイコンさんの動画見ながら Claude-Code-Communication リポジトリフォークしていプロンプトを汎用的になるようにいじったらできました！🎉 https://t.co/tQagPKZqnk」 / X](https://x.com/akira_papa_IT/status/1932547492199182733)

![Xユーザーのあきらパパ【生成AI活用エンジニア&３児のパパ】さん: 「【tmuxでClaude CodeのMaxプランでAI組織を動かし放題のローカル環境ができた〜〜〜！！！🔥🔥🔥🙌☺️】 ダイコンさんの動画見ながらClaude-Code-Communicationリポジトリフォークしていプロンプトを汎用的になるようにいじったらできました！🎉 https://t.co/tQagPKZqnk」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [claude code でローカルな MCP サーバーを叩けるようにする](https://zenn.dev/mizchi/articles/claude-local-mcp-server)

![claude code でローカルなMCPサーバーを叩けるようにする](https://res.cloudinary.com/zenn/image/upload/s--miyzM-f0--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:claude%2520code%2520%25E3%2581%25A7%25E3%2583%25AD%25E3%2583%25BC%25E3%2582%25AB%25E3%2583%25AB%25E3%2581%25AAMCP%25E3%2582%25B5%25E3%2583%25BC%25E3%2583%2590%25E3%2583%25BC%25E3%2582%2592%25E5%258F%25A9%25E3%2581%2591%25E3%2582%258B%25E3%2582%2588%25E3%2581%2586%25E3%2581%25AB%25E3%2581%2599%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:mizchi%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2liclRHT052Z3d3ay1fNGxlcVk4TGNGSlNuX0FoWnpEWVlKaXJNcWc9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [container-use やってみた - Qiita](https://qiita.com/moritalous/items/b0ec9548b8104f1bd375?utm_campaign=post_article&utm_medium=twitter&utm_source=twitter_share)

![container-useやってみた - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Farticle-ogp-background-afbab5eb44e0b055cce1258705637a91.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1pbWFnZS1zdG9yZSUyRjAlMkY0MTU3NCUyRjRlZjYzODMyOTNiYTllNmNlZmJiOThmYzhjNjViZDRjZjZjYjM4YTIlMkZ4X2xhcmdlLnBuZyUzRjE1OTU2NDI5ODU_aXhsaWI9cmItNC4wLjAmYXI9MSUzQTEmZml0PWNyb3AmbWFzaz1lbGxpcHNlJmJnPUZGRkZGRiZmbT1wbmczMiZzPWU4MWNjMjdlNDAzYTAzODAzYTAxZWE4M2NkNDg3Y2Y2%26blend-x%3D120%26blend-y%3D467%26blend-w%3D82%26blend-h%3D82%26blend-mode%3Dnormal%26s%3Dec919ed15baa6bac134e69e130b6e800?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9Y29udGFpbmVyLXVzZSVFMyU4MiU4NCVFMyU4MSVBMyVFMyU4MSVBNiVFMyU4MSVCRiVFMyU4MSU5RiZ0eHQtYWxpZ249bGVmdCUyQ3RvcCZ0eHQtY29sb3I9JTIzMUUyMTIxJnR4dC1mb250PUhpcmFnaW5vJTIwU2FucyUyMFc2JnR4dC1zaXplPTU2JnR4dC1wYWQ9MCZzPTg2NGNjYzJmNTU1NjcwYWRhOTIyYTI1MjU2MmFkYjdm&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDBtb3JpdGFsb3VzJnR4dC1jb2xvcj0lMjMxRTIxMjEmdHh0LWZvbnQ9SGlyYWdpbm8lMjBTYW5zJTIwVzYmdHh0LXNpemU9MzYmdHh0LXBhZD0wJnM9NTE5MDJlZTJlOTExNTEzZmVhMTBjNzY4YjZmNjRkM2I&blend-x=242&blend-y=480&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&s=64baeb4c583bb2d0fa670ecb293df7a5)

ロゴが可愛いと評判の container-use をやってみました。 GitHub リポジトリはこちら container-use とは README より Container Use lets each of your coding agents have thei...

---

### [Claude Code を並列組織化して Claude Code "Company"にする tmux コマンド集](https://zenn.dev/kazuph/articles/beb87d102bd4f5)

![Claude Codeを並列組織化してClaude Code "Company"にするtmuxコマンド集](https://res.cloudinary.com/zenn/image/upload/s--AroizRzh--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2582%2592%25E4%25B8%25A6%25E5%2588%2597%25E7%25B5%2584%25E7%25B9%2594%25E5%258C%2596%25E3%2581%2597%25E3%2581%25A6Claude%2520Code%2520%2522Company%2522%25E3%2581%25AB%25E3%2581%2599%25E3%2582%258Btmux%25E3%2582%25B3%25E3%2583%259E%25E3%2583%25B3%25E3%2583%2589%25E9%259B%2586%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:kazuph%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzFjNmY3ODBlZDYuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Firebase AI Logic for Unity：Live API 実装ガイド　リアルタイム音声対話を実現する](https://zenn.dev/hololab/articles/firebase-ai-logic-unity-live-api)

![Firebase AI Logic for Unity：Live API実装ガイド　リアルタイム音声対話を実現する](https://res.cloudinary.com/zenn/image/upload/s--cEI_7A37--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Firebase%2520AI%2520Logic%2520for%2520Unity%25EF%25BC%259ALive%2520API%25E5%25AE%259F%25E8%25A3%2585%25E3%2582%25AC%25E3%2582%25A4%25E3%2583%2589%25E3%2580%2580%25E3%2583%25AA%25E3%2582%25A2%25E3%2583%25AB%25E3%2582%25BF%25E3%2582%25A4%25E3%2583%25A0%25E9%259F%25B3%25E5%25A3%25B0%25E5%25AF%25BE%25E8%25A9%25B1%25E3%2582%2592%25E5%25AE%259F%25E7%258F%25BE%25E3%2581%2599%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:FumiyaHr%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2RkMzA4MzIwZTkuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E3%2583%259B%25E3%2583%25AD%25E3%2583%25A9%25E3%2583%259C%25E3%2581%25AE%25E3%2583%2586%25E3%2583%2583%25E3%2582%25AF%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2dwa0c0REFqSWJBbHpvM1lJR2FkdjhMTDJLT0pnTUZmOTN5NTdoPXM5Ni1j%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [【完全攻略】バイブコーディング入門！駆け出し開発者はこれを見て学ぼう！AI 駆動開発のプロが徹底解説｜まさお@未経験からプロまで AI 活用](https://note.com/masa_wunder/n/n01c1ac666c4b)

![【完全攻略】バイブコーディング入門！駆け出し開発者はこれを見て学ぼう！AI駆動開発のプロが徹底解説｜まさお@未経験からプロまでAI活用](https://assets.st-note.com/production/uploads/images/194882035/rectangle_large_type_2_307bb80ddaa79e69e2c6404fb5dfabab.png?fit=bounds&quality=85&width=1280)

2025 年 2 月、元 OpenAI／Tesla のエンジニア アンドレイ・カルパシー氏が X（旧 Twitter）に投稿した一言 “There’s a new kind of coding I call vibe coding …” 上記のツイートが火種となり、“バイブコーディング” の呼称が一気に広まりました。同氏は「コードの細部を忘れ、アイデアの雰囲気だけを AI に委ねる」と説明し、そのツイートは瞬く間に開発コミュニティで拡散。 海外の技術誌 Ars Technica も同月に特集を組み、誕生直後のムーブメントを報じました https://x.com/karpathy/

---

### [すべてのコーディングエージェントに独立した開発用コンテナ環境を与えられる「Container Use」、Docker 創業者がオープンソースで公開](https://www.publickey1.jp/blog/25/container_usedocker.html)

![すべてのコーディングエージェントに独立した開発用コンテナ環境を与えられる「Container Use」、Docker創業者がオープンソースで公開](https://www.publickey1.jp/2025/Gs0O68JaoAEExJu.jpg)

Docker 創業者で現在はプラットフォームエンジニアリングのツールを開発する Dagger 社の創業者兼 CTO の Solomon Hykes（ソロモン・ハイクス）氏は、すべてのコーディングエージェントに対してそれぞれ独立した開発用のコンテナ環境を...

---

### [Claude Code (MAX plan) + gh コマンド + 英語プロンプトが一旦完成系だと思った話](https://zenn.dev/engine0606/articles/9201ff4c3e837d)

![Claude Code (MAX plan) + ghコマンド + 英語プロンプトが一旦完成系だと思った話](https://res.cloudinary.com/zenn/image/upload/s--5j3Vbv9e--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%2520%2528MAX%2520plan%2529%2520%252B%2520gh%25E3%2582%25B3%25E3%2583%259E%25E3%2583%25B3%25E3%2583%2589%2520%252B%2520%25E8%258B%25B1%25E8%25AA%259E%25E3%2583%2597%25E3%2583%25AD%25E3%2583%25B3%25E3%2583%2597%25E3%2583%2588%25E3%2581%258C%25E4%25B8%2580%25E6%2597%25A6%25E5%25AE%258C%25E6%2588%2590%25E7%25B3%25BB%25E3%2581%25A0%25E3%2581%25A8%25E6%2580%259D%25E3%2581%25A3%25E3%2581%259F%25E8%25A9%25B1%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Tomohide%2520Hirakawa%25EF%25BC%2588...%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzJmMTBmNjg5MjkuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E6%25A0%25AA%25E5%25BC%258F%25E4%25BC%259A%25E7%25A4%25BEen-gine%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2kwd3htVl82Um5nYnBFTUFCbnkzbE4yUER3OF9tVDNJZDhEVVM5QUE9czI1MC1j%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Gemini x Stitch を使って、デザインセンス皆無の男がイケてる UI 生成の限界に挑戦してみる - Qiita](https://qiita.com/zawatti/items/aa761adbb4829c0f89d4)

![Gemini x Stitchを使って、デザインセンス皆無の男がイケてるUI生成の限界に挑戦してみる - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Farticle-ogp-background-afbab5eb44e0b055cce1258705637a91.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1pbWFnZS1zdG9yZSUyRjAlMkYzNDc4ODUzJTJGNDk0ODIxNDdlZmFlMmE3OGY1MzgwMmM4NjMyNjczZmYyYjRhMWIwNCUyRnhfbGFyZ2UucG5nJTNGMTY4NjgxNDM3Nj9peGxpYj1yYi00LjAuMCZhcj0xJTNBMSZmaXQ9Y3JvcCZtYXNrPWVsbGlwc2UmYmc9RkZGRkZGJmZtPXBuZzMyJnM9NTQ3Y2I2NGQ5NzIxYTMxYzVhZjhhYWFlMTA4NTNhNGQ%26blend-x%3D120%26blend-y%3D462%26blend-w%3D90%26blend-h%3D90%26blend-mode%3Dnormal%26mark64%3DaHR0cHM6Ly9xaWl0YS1vcmdhbml6YXRpb24taW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1vcmdhbml6YXRpb24taW1hZ2UlMkZlZmNlZmNmMGNiOTU0MzQwOWYxMmZkZGMzMGQ2NDFmZmRmMTI0N2NhJTJGb3JpZ2luYWwuanBnJTNGMTYxNTk2OTg5Mj9peGxpYj1yYi00LjAuMCZ3PTQ0Jmg9NDQmZml0PWNyb3AmbWFzaz1jb3JuZXJzJmNvcm5lci1yYWRpdXM9OCZiZz1GRkZGRkYmYm9yZGVyPTIlMkNGRkZGRkYmZm09cG5nMzImcz1hZjRmZmZkZjM4NDE0YjIzMWRkZmZhZDJjZjllMTJjOA%26mark-x%3D186%26mark-y%3D515%26mark-w%3D40%26mark-h%3D40%26s%3Df6262193319d415c42cfd87aba5c9471?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9R2VtaW5pJTIweCUyMFN0aXRjaCVFMyU4MiU5MiVFNCVCRCVCRiVFMyU4MSVBMyVFMyU4MSVBNiVFMyU4MCU4MSVFMyU4MyU4NyVFMyU4MiVCNiVFMyU4MiVBNCVFMyU4MyVCMyVFMyU4MiVCQiVFMyU4MyVCMyVFMyU4MiVCOSVFNyU5QSU4NiVFNyU4NCVBMSVFMyU4MSVBRSVFNyU5NCVCNyVFMyU4MSU4QyVFMyU4MiVBNCVFMyU4MiVCMSVFMyU4MSVBNiVFMyU4MiU4QlVJJUU3JTk0JTlGJUU2JTg4JTkwJUUzJTgxJUFFJUU5JTk5JTkwJUU3JTk1JThDJUUzJTgxJUFCJUU2JThDJTkxJUU2JTg4JUE2JUUzJTgxJTk3JUUzJTgxJUE2JUUzJTgxJUJGJUUzJTgyJThCJnR4dC1hbGlnbj1sZWZ0JTJDdG9wJnR4dC1jb2xvcj0lMjMxRTIxMjEmdHh0LWZvbnQ9SGlyYWdpbm8lMjBTYW5zJTIwVzYmdHh0LXNpemU9NTYmdHh0LXBhZD0wJnM9MDc1YzlmOTRlZGJkZjFhZmYwMWU3MTZhZmIwZmRiOTY&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDB6YXdhdHRpJnR4dC1jb2xvcj0lMjMxRTIxMjEmdHh0LWZvbnQ9SGlyYWdpbm8lMjBTYW5zJTIwVzYmdHh0LXNpemU9MzYmdHh0LXBhZD0wJnM9YWM2ZTI4ZmY4NzMxNGRhNzIzYmIzZjM2NmRlZmRmODk&blend-x=242&blend-y=454&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&txt64=5qCq5byP5Lya56S-44OO44OZ44Or44Ov44O844Kv44K5&txt-x=242&txt-y=539&txt-width=838&txt-clip=end%2Cellipsis&txt-color=%231E2121&txt-font=Hiragino%20Sans%20W6&txt-size=28&s=21245e5c921674a7c95f264fa82e239e)

はじめに こんにちは。ノベルワークス所属のザワッチです！ 最近、Google が出した UI 生成ツール「Stitch」を使って、非デザイナーでかつデザインセンス皆無の男がイケてる UI 生成の限界に挑戦してみた記事になります。 イケてる UI とは何なのかを AI と壁打ち協力し、自分な...

---

### [Claude Code を試してみました・Tips メモ](https://zenn.dev/karaage0703/articles/6699045b3cec5c)

![Claude Codeを試してみました・Tipsメモ](https://res.cloudinary.com/zenn/image/upload/s--49tgRp9S--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2582%2592%25E8%25A9%25A6%25E3%2581%2597%25E3%2581%25A6%25E3%2581%25BF%25E3%2581%25BE%25E3%2581%2597%25E3%2581%259F%25E3%2583%25BBTips%25E3%2583%25A1%25E3%2583%25A2%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%258B%25E3%2582%2589%25E3%2581%2582%25E3%2581%2592%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2hDZEtvakJfZXdDTjNCV1Z0WXIteFNIZ0hmRjlXZmt3QzI5c0Y0aXYwPXMyNTAtYw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [もう RAG を自作しなくていい！Vertex AI Search のススメ](https://zenn.dev/progate/articles/benefit-of-vertex-ai)

![もうRAGを自作しなくていい！Vertex AI Search のススメ](https://res.cloudinary.com/zenn/image/upload/s--V0ewEzKk--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E3%2582%2582%25E3%2581%2586RAG%25E3%2582%2592%25E8%2587%25AA%25E4%25BD%259C%25E3%2581%2597%25E3%2581%25AA%25E3%2581%258F%25E3%2581%25A6%25E3%2581%2584%25E3%2581%2584%25EF%25BC%2581Vertex%2520AI%2520Search%2520%25E3%2581%25AE%25E3%2582%25B9%25E3%2582%25B9%25E3%2583%25A1%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Godai%2520Hori%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2UzOTZjNjhlM2MuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:Progate%2520Tech%2520Blog%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzU2MzlkZTY4MGYuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Pro（$20）プランでゼロから始める Claude Code](https://zenn.dev/asap/articles/700168965fdb7b)

![Claude Pro（$20）プランでゼロから始めるClaude Code](https://res.cloudinary.com/zenn/image/upload/s--o927mcY9--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Pro%25EF%25BC%2588%252420%25EF%25BC%2589%25E3%2583%2597%25E3%2583%25A9%25E3%2583%25B3%25E3%2581%25A7%25E3%2582%25BC%25E3%2583%25AD%25E3%2581%258B%25E3%2582%2589%25E5%25A7%258B%25E3%2582%2581%25E3%2582%258BClaude%2520Code%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:asap%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2VhYjVhYTQ1MTkuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [「ファイル復元トレーニング」という Cursor ルールのトレーニング方法](https://zenn.dev/loglass/articles/10cb41eff3139d)

![「ファイル復元トレーニング」というCursorルールのトレーニング方法](https://res.cloudinary.com/zenn/image/upload/s--nEZ8f0Rt--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E3%2580%258C%25E3%2583%2595%25E3%2582%25A1%25E3%2582%25A4%25E3%2583%25AB%25E5%25BE%25A9%25E5%2585%2583%25E3%2583%2588%25E3%2583%25AC%25E3%2583%25BC%25E3%2583%258B%25E3%2583%25B3%25E3%2582%25B0%25E3%2580%258D%25E3%2581%25A8%25E3%2581%2584%25E3%2581%2586Cursor%25E3%2583%25AB%25E3%2583%25BC%25E3%2583%25AB%25E3%2581%25AE%25E3%2583%2588%25E3%2583%25AC%25E3%2583%25BC%25E3%2583%258B%25E3%2583%25B3%25E3%2582%25B0%25E6%2596%25B9%25E6%25B3%2595%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Yuito%2520Sato%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzRlNWQ4ZTRjZjguanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E6%25A0%25AA%25E5%25BC%258F%25E4%25BC%259A%25E7%25A4%25BE%25E3%2583%25AD%25E3%2582%25B0%25E3%2583%25A9%25E3%2582%25B9%2520%25E3%2583%2586%25E3%2583%2583%25E3%2582%25AF%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2M4NTA0YzQyMGQuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Anthropic で利用されているモダンな Python 開発のベストプラクティス](https://zenn.dev/yareyare/articles/d67aa75b37537c)

![Anthropicで利用されているモダンなPython開発のベストプラクティス](https://res.cloudinary.com/zenn/image/upload/s--aTXjp4Rj--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Anthropic%25E3%2581%25A7%25E5%2588%25A9%25E7%2594%25A8%25E3%2581%2595%25E3%2582%258C%25E3%2581%25A6%25E3%2581%2584%25E3%2582%258B%25E3%2583%25A2%25E3%2583%2580%25E3%2583%25B3%25E3%2581%25AAPython%25E9%2596%258B%25E7%2599%25BA%25E3%2581%25AE%25E3%2583%2599%25E3%2582%25B9%25E3%2583%2588%25E3%2583%2597%25E3%2583%25A9%25E3%2582%25AF%25E3%2583%2586%25E3%2582%25A3%25E3%2582%25B9%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E7%2594%25B0%25E4%25B8%25AD%25E5%25A4%25AA%25E9%2583%258E%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUNnOG9jSjZWcVBoWEgwaXVsS05VYlRVOElzXzVQbGVvWV9DVk5VZVZnbjhDRWkwPXM5Ni1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code の settings.json は設定した方がいい - じゃあ、おうちで学べる](https://syu-m-5151.hatenablog.com/entry/2025/06/05/134147)

![Claude Code の settings.json は設定した方がいい - じゃあ、おうちで学べる](https://ogimage.blog.st-hatena.com/8454420450094081900/6802418398461810912/1749179621)

はじめに Claude Code 使ってますか？ターミナルから Claude に直接コーディングタスクを投げられる便利なツールなんですが、デフォルト設定のまま使うのはちょっともったいない。というかいちいちいろんなことを聞いてきてめちゃくちゃダルい。 syu-m-5151.hatenablog.com settings.json をちゃんと設定すると、セキュリティも保ちつつ、もっと快適に使えるようになります。全体的に疲れている時の~/.claude/settings.json と~/.claude/CLAUDE.md · GitHub 私のデフォルトの設定も公開してますのでよかったら参考にしてく…

---

### [Claude Code / Claude Code Action を Google Cloud Vertex AI 経由で使う](https://zenn.dev/team_zenn/articles/claude-code-vertex-ai)

![Claude Code / Claude Code Action を Google Cloud Vertex AI 経由で使う](https://res.cloudinary.com/zenn/image/upload/s--IcoUu40e--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%2520%252F%2520Claude%2520Code%2520Action%2520%25E3%2582%2592%2520Google%2520Cloud%2520Vertex%2520AI...%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:waddy_u%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzYzOTk2NzhlNmIuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/g_south_west%2Ch_34%2Cl_default:og-publication-pro-mark-xcosax%2Cw_34%2Cx_217%2Cy_158/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:Zenn%2520Tech%2520Blog%2Cx_255%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2FiMjdhZGEwNDcuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code Action をさっそくレビューしてみた！ - Qiita](https://qiita.com/kyuko/items/ad894bac5ba516683387)

![Claude Code Actionをさっそくレビューしてみた！ - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Farticle-ogp-background-afbab5eb44e0b055cce1258705637a91.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRmF2YXRhcnMxLmdpdGh1YnVzZXJjb250ZW50LmNvbSUyRnUlMkY1NDQzNDk3OCUzRnYlM0Q0P2l4bGliPXJiLTQuMC4wJmFyPTElM0ExJmZpdD1jcm9wJm1hc2s9ZWxsaXBzZSZiZz1GRkZGRkYmZm09cG5nMzImcz0wNDZlN2U3Mzc5NGZlY2NmNjczYTU3OGUwNmE4N2JhNA%26blend-x%3D120%26blend-y%3D462%26blend-w%3D90%26blend-h%3D90%26blend-mode%3Dnormal%26mark64%3DaHR0cHM6Ly9xaWl0YS1vcmdhbml6YXRpb24taW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1vcmdhbml6YXRpb24taW1hZ2UlMkYxZTIwZGI1ZTdlNDA3ZWFlN2I5NzBlYzk5OTg4MGRjOGMzY2MwZjY0JTJGb3JpZ2luYWwuanBnJTNGMTY2NzI3NDk2Mz9peGxpYj1yYi00LjAuMCZ3PTQ0Jmg9NDQmZml0PWNyb3AmbWFzaz1jb3JuZXJzJmNvcm5lci1yYWRpdXM9OCZiZz1GRkZGRkYmYm9yZGVyPTIlMkNGRkZGRkYmZm09cG5nMzImcz0xMzQ4OTg3MjlkMzMwYTdiNWRhMzRkOGU2MzVmZjIxOA%26mark-x%3D186%26mark-y%3D515%26mark-w%3D40%26mark-h%3D40%26s%3Db2d30a0c981b7f074b9f2985c08cb84c?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9Q2xhdWRlJTIwQ29kZSUyMEFjdGlvbiVFMyU4MiU5MiVFMyU4MSU5NSVFMyU4MSVBMyVFMyU4MSU5RCVFMyU4MSU4RiVFMyU4MyVBQyVFMyU4MyU5MyVFMyU4MyVBNSVFMyU4MyVCQyVFMyU4MSU5NyVFMyU4MSVBNiVFMyU4MSVCRiVFMyU4MSU5RiVFRiVCQyU4MSZ0eHQtYWxpZ249bGVmdCUyQ3RvcCZ0eHQtY29sb3I9JTIzMUUyMTIxJnR4dC1mb250PUhpcmFnaW5vJTIwU2FucyUyMFc2JnR4dC1zaXplPTU2JnR4dC1wYWQ9MCZzPTkwYzE1MWE3ZWI4N2M2ZjhiMTYyN2ZhOTdlM2JlZGRh&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDBreXVrbyZ0eHQtY29sb3I9JTIzMUUyMTIxJnR4dC1mb250PUhpcmFnaW5vJTIwU2FucyUyMFc2JnR4dC1zaXplPTM2JnR4dC1wYWQ9MCZzPWMxMTY3MjE5MDQ5M2RiZGU0NzRmOTc1YzIxZjUwYmQx&blend-x=242&blend-y=454&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&txt64=S0RESeOCouOCuOODo-OCpOODq-mWi-eZuuOCu-ODs-OCv-ODvOagquW8j-S8muekvg&txt-x=242&txt-y=539&txt-width=838&txt-clip=end%2Cellipsis&txt-color=%231E2121&txt-font=Hiragino%20Sans%20W6&txt-size=28&s=123842026c3a3cc4091b9a268b085dd5)

おひさしぶりです。ひさふるです。 先ほど(日本時間 5 月 23 日未明)に行われた Anthropic の開発者向けイベント Code with Claude 内の発表で、コーディングエージェント"Claude Code"が GitHub Actions として利用出来るようになったことが明...

---

### [AWS の Bedrock で Claude 4 と Claude Code をセキュアに活用しよう！ - Qiita](https://qiita.com/moritalous/items/9da3e2538c9507890e40)

![AWSのBedrockでClaude 4とClaude Codeをセキュアに活用しよう！ - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Farticle-ogp-background-afbab5eb44e0b055cce1258705637a91.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1pbWFnZS1zdG9yZSUyRjAlMkY0MTU3NCUyRjRlZjYzODMyOTNiYTllNmNlZmJiOThmYzhjNjViZDRjZjZjYjM4YTIlMkZ4X2xhcmdlLnBuZyUzRjE1OTU2NDI5ODU_aXhsaWI9cmItNC4wLjAmYXI9MSUzQTEmZml0PWNyb3AmbWFzaz1lbGxpcHNlJmJnPUZGRkZGRiZmbT1wbmczMiZzPWU4MWNjMjdlNDAzYTAzODAzYTAxZWE4M2NkNDg3Y2Y2%26blend-x%3D120%26blend-y%3D467%26blend-w%3D82%26blend-h%3D82%26blend-mode%3Dnormal%26s%3Dec919ed15baa6bac134e69e130b6e800?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9QVdTJUUzJTgxJUFFQmVkcm9jayVFMyU4MSVBN0NsYXVkZSUyMDQlRTMlODElQThDbGF1ZGUlMjBDb2RlJUUzJTgyJTkyJUUzJTgyJUJCJUUzJTgyJUFEJUUzJTgzJUE1JUUzJTgyJUEyJUUzJTgxJUFCJUU2JUI0JUJCJUU3JTk0JUE4JUUzJTgxJTk3JUUzJTgyJTg4JUUzJTgxJTg2JUVGJUJDJTgxJnR4dC1hbGlnbj1sZWZ0JTJDdG9wJnR4dC1jb2xvcj0lMjMxRTIxMjEmdHh0LWZvbnQ9SGlyYWdpbm8lMjBTYW5zJTIwVzYmdHh0LXNpemU9NTYmdHh0LXBhZD0wJnM9MDdhYTY1NTRiNDUxNGVkYmI2NTUxY2QyMmMxNmQ2OTU&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDBtb3JpdGFsb3VzJnR4dC1jb2xvcj0lMjMxRTIxMjEmdHh0LWZvbnQ9SGlyYWdpbm8lMjBTYW5zJTIwVzYmdHh0LXNpemU9MzYmdHh0LXBhZD0wJnM9NTE5MDJlZTJlOTExNTEzZmVhMTBjNzY4YjZmNjRkM2I&blend-x=242&blend-y=480&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&s=273282f09dfbca018423c590ec38f29f)

自己紹介 profile: name: 森田 和明 company: 富士ソフト株式会社 position: title: 主任 / フェロー specialization: アーキテクト・エバンジェリスト AWS Certifi...

---

### [X ユーザーのぬこぬこさん: 「Mastra 101 Mastra AI のローカル MCP サーバを用いたコース。Cursor や Windsurf、VSCode にて専用の MCP を指定することで学べる。進捗管理機能やシラバスの確認もできる。現時点で「エージェントの作り方」「ツールや MCP の追加」「メモリー機能の追加」の三つのコースが用意、分量は計 12」 / X](https://x.com/schroneko/status/1930342065524879860)

![Xユーザーのぬこぬこさん: 「Mastra 101  Mastra AI のローカル MCP サーバを用いたコース。Cursor や Windsurf、VSCode にて専用の MCP を指定することで学べる。進捗管理機能やシラバスの確認もできる。現時点で「エージェントの作り方」「ツールや MCP の追加」「メモリー機能の追加」の三つのコースが用意、分量は計 12」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーのぬこぬこさん: 「Claude Code が Max プランだけでなく、Pro プランからも使えるように！」 / X](https://x.com/schroneko/status/1930309185130115161)

![Xユーザーのぬこぬこさん: 「Claude Code が Max プランだけでなく、Pro プランからも使えるように！」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Claude Code のすすめ](https://speakerdeck.com/schroneko/getting-started-with-claude-code)

![Claude Code のすすめ](https://files.speakerdeck.com/presentations/d25a0c8d12644628866d1c285a97c985/slide_0.jpg?35340961)

---

### [やさしい Claude Code 入門](https://speakerdeck.com/minorun365/yasasiiclaude-coderu-men)

![やさしいClaude Code入門](https://files.speakerdeck.com/presentations/6d2bd40c011342bfb974c58c5c4d54fd/slide_0.jpg?35329547)

話題の Claude 4 と Claude Code に入門！（KAG と学ぼう！勉強会）
https://www.youtube.com/live/8BPfZKIa51k

---

### [日本語医療特化型 LLM の現状と展望](https://zenn.dev/mkj/articles/b04bdede9bc3d6)

![日本語医療特化型LLMの現状と展望](https://res.cloudinary.com/zenn/image/upload/s--zdqTk-zT--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E6%2597%25A5%25E6%259C%25AC%25E8%25AA%259E%25E5%258C%25BB%25E7%2599%2582%25E7%2589%25B9%25E5%258C%2596%25E5%259E%258BLLM%25E3%2581%25AE%25E7%258F%25BE%25E7%258A%25B6%25E3%2581%25A8%25E5%25B1%2595%25E6%259C%259B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:sha%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2U2NGM3ZTBkMzIuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/g_south_west%2Ch_34%2Cl_default:og-publication-pro-mark-xcosax%2Cw_34%2Cx_217%2Cy_158/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E6%259D%25BE%25E5%25B0%25BE%25E7%25A0%2594%25E7%25A9%25B6%25E6%2589%2580%25E3%2583%2586%25E3%2583%2583%25E3%2582%25AF%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_255%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUNnOG9jTFZmTUtzeTN5UUM2WlFJSTZ2VlFRN2VnZWtMM1o0alE2bnVhN1NSUW9TTWJBMmpBPXM5Ni1j%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Cursor から Claude Code への乗り換えメモ｜ shu223](https://note.com/shu223/n/n2005bee00b09)

![CursorからClaude Codeへの乗り換えメモ｜shu223](https://assets.st-note.com/production/uploads/images/197734279/rectangle_large_type_2_5b8aeb3d6499b7cfb4fecb9e61d22707.png?fit=bounds&quality=85&width=1280)

Claude Code は、登場時に一度インストールしてみたものの「そもそも CLI に苦手意識がある自分用ではないな」と思って何も試さずにアンイストールしたのだった。 その後乗り換えを検討したこともあるが、「今は Cursor で困ってないしまだいいや」と結局手を出さずじまいだった。 しかし昨今の盛り上がりを横目で見ていて、やっぱり隣の芝が青く見えるとか FOMO ってるとかのレベルを超えて Claude Code + MAX プランが良さそうだなと思えてきたので、めんどくさかろうが現状（Cursor）に満足してようが試すことにした。 「Cursor のアレ、Claude Code ではどうやるんだ

---

### [AI でプログラマ不要になるというのは、プログラミング言語構文わかればプログラム組めるという誤解に基づくのでは - きしだの Hatena](https://nowokay.hatenablog.com/entry/2025/06/23/113527)

![AIでプログラマ不要になるというのは、プログラミング言語構文わかればプログラム組めるという誤解に基づくのでは - きしだのHatena](https://cdn.image.st-hatena.com/image/scale/b117617f636b8a58924f9275517e7892c33923f2/backend=imagemagick;version=1;width=1300/https%3A%2F%2Fcdn-ak.f.st-hatena.com%2Fimages%2Ffotolife%2Fn%2Fnowokay%2F20250623%2F20250623114240.png)

AI で日本語で指示をあたえればプログラムを作ってくれるようになって、プログラミング知識がなくても誰でもプログラムが組めるとか、プログラマが不要になるとかいう話が盛り上がってますね。 けど、実際にプログラマをやって、AI コーディングエージェントを使っていれば、プログラミング知識がなくても可能な領域というのはそんなに広くないことを感じていると思います。 たとえば、ほぼプロンプト一発で作ってもらった刺身タンポポゲームがあります。 このプロンプトはこんな感じです。 刺身にタンポポを乗せるゲームを Java の Swing で作って。 刺身かネコが 0.75 秒ごとに表示されます。 刺身は、白い皿に、赤い板状の切り…

---

### [Claude Code 時代のソフトウェアエンジニア生存戦略｜ suthio](https://note.com/suthio/n/n4f79fbe4efda?sub_rt=share_pb)

![Claude Code時代のソフトウェアエンジニア生存戦略｜suthio](https://assets.st-note.com/production/uploads/images/197611055/rectangle_large_type_2_a981561b24ea51b02c900bf5941cf776.png?fit=bounds&quality=85&width=1280)

Claude Code が変えた開発の風景 Claude Code を使い始めて約 1 ヶ月経ちますが「Claude Code を使ってから、開発の概念が根本的に変わった」と僕は思ってる。 Cline や Cursor Agent の登場でもでも相当変わったと思う。でも Claude Code はそれ以上の変化だと僕は感じている。何が根本的に違うのか。 自走力の高い Claude Code - ファイルを読み、修正し、テストを実行し、エラーを解決する。まるでペアプロしているような体験。 コードを書く能力が高い Claude 4 Opus - 複雑なロジックも正確に実装できる圧倒的なコード

---

### [【Claude Code】カスタム Slash Command の作り方とコマンド例を紹介する](https://zenn.dev/oikon/articles/cb11b84f891228)

![【Claude Code】カスタムSlash Commandの作り方とコマンド例を紹介する](https://res.cloudinary.com/zenn/image/upload/s--huc_qV52--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E3%2580%2590Claude%2520Code%25E3%2580%2591%25E3%2582%25AB%25E3%2582%25B9%25E3%2582%25BF%25E3%2583%25A0Slash%2520Command%25E3%2581%25AE%25E4%25BD%259C%25E3%2582%258A%25E6%2596%25B9%25E3%2581%25A8%25E3%2582%25B3%25E3%2583%259E%25E3%2583%25B3%25E3%2583%2589%25E4%25BE%258B%25E3%2582%2592%25E7%25B4%25B9%25E4%25BB%258B%25E3%2581%2599%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Oikon%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzFlNjI2MjNlZTQuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーのミロさん: 「Claude Code をチャット画面経由で使えるようにする VSCode の拡張機能が出てた。 Cursor に慣れてるから Claude Code を同じように使いたいって人にはよさそう https://t.co/jswEbjNpZ9 https://t.co/2hpaPSar4L」 / X](https://x.com/ml0_1337/status/1936235733154738225)

![Xユーザーのミロさん: 「Claude Codeをチャット画面経由で使えるようにするVSCodeの拡張機能が出てた。  Cursorに慣れてるからClaude Codeを同じように使いたいって人にはよさそう  https://t.co/jswEbjNpZ9 https://t.co/2hpaPSar4L」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーのうえぞう@うな技研代表さん: 「📣 リリース速報 AI アバター開発フレームワークの AIAvatarKit v0.7.5 リリースしたよ〜 ✅ ノイズに強いターンエンド判定 ✅AmiVoice の音声認識に対応 ✅STT/LLM/TTS 設定管理用 API の追加　ほか 動画は騒音下でも会話できてるの図。入力レベルがほぼ一定だけど人の声を拾ってターンエンド判定してる https://t.co/vbVYhDfIwG」 / X](https://x.com/uezochan/status/1931715686113460421)

![Xユーザーのうえぞう@うな技研代表さん: 「📣リリース速報 AIアバター開発フレームワークのAIAvatarKit v0.7.5リリースしたよ〜  ✅ノイズに強いターンエンド判定 ✅AmiVoiceの音声認識に対応 ✅STT/LLM/TTS設定管理用APIの追加　ほか  動画は騒音下でも会話できてるの図。入力レベルがほぼ一定だけど人の声を拾ってターンエンド判定してる https://t.co/vbVYhDfIwG」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの Maki@Sunwood AI Labs.さん: 「「編集可能グラフィックレコーディングプロンプト v3.0 ～涼雅（りょうが）～」リリース これで編集可能かつ、ダークテーマへの変更も可能になりました！ ーーー 📒 プロンプトーーー https://t.co/HYOHRTsrAs」 / X](https://x.com/hAru_mAki_ch/status/1936032997029167410)

![XユーザーのMaki@Sunwood AI Labs.さん: 「「編集可能グラフィックレコーディングプロンプト v3.0 ～涼雅（りょうが）～」リリース これで編集可能かつ、ダークテーマへの変更も可能になりました！  ーーー📒プロンプトーーー https://t.co/HYOHRTsrAs」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Claude Code が GitHub の Issue 内の画像を読めるようにする gh-asset という OSS を公開しました](https://zenn.dev/loglass/articles/c244b433b4d03c)

![Claude CodeがGitHubのIssue内の画像を読めるようにするgh-assetというOSSを公開しました](https://res.cloudinary.com/zenn/image/upload/s--P7O1cjOK--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%258CGitHub%25E3%2581%25AEIssue%25E5%2586%2585%25E3%2581%25AE%25E7%2594%25BB%25E5%2583%258F%25E3%2582%2592%25E8%25AA%25AD%25E3%2582%2581%25E3%2582%258B%25E3%2582%2588%25E3%2581%2586%25E3%2581%25AB%25E3%2581%2599%25E3%2582%258Bgh-asset%25E3%2581%25A8%25E3%2581%2584%25E3%2581%2586OSS%25E3%2582%2592%25E5%2585%25AC%25E9%2596%258B%25E3%2581%2597%25E3%2581%25BE%25E3%2581%2597%25E3%2581%259F%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Yuito%2520Sato%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzRlNWQ4ZTRjZjguanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E6%25A0%25AA%25E5%25BC%258F%25E4%25BC%259A%25E7%25A4%25BE%25E3%2583%25AD%25E3%2582%25B0%25E3%2583%25A9%25E3%2582%25B9%2520%25E3%2583%2586%25E3%2583%2583%25E3%2582%25AF%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2M4NTA0YzQyMGQuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [【実体験】Claude Code と Cursor、1 週間使い倒して分かった本当のコスパ - Qiita](https://qiita.com/satokenichi/items/e2e2a837d92c88dd3025)

![【実体験】Claude CodeとCursor、1週間使い倒して分かった本当のコスパ - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Ftech-festa-ogp-background-4b5015b2c518c7e6b9062a7c9f5f5e90.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnFpaXRhLWltYWdlLXN0b3JlLnMzLmFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkYwJTJGNDA0MzY5NyUyRnByb2ZpbGUtaW1hZ2VzJTJGMTc0ODQwODc5MT9peGxpYj1yYi00LjAuMCZhcj0xJTNBMSZmaXQ9Y3JvcCZtYXNrPWVsbGlwc2UmYmc9RkZGRkZGJmZtPXBuZzMyJnM9OTI5MGEyMzMyYzE4MGQ5ZmJhMmNmMDQzZGJiMTIyNzk%26blend-x%3D120%26blend-y%3D467%26blend-w%3D82%26blend-h%3D82%26blend-mode%3Dnormal%26s%3D5c1d02bad34ba4abdea413c7174ad80e?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9JUUzJTgwJTkwJUU1JUFFJTlGJUU0JUJEJTkzJUU5JUE4JTkzJUUzJTgwJTkxQ2xhdWRlJTIwQ29kZSVFMyU4MSVBOEN1cnNvciVFMyU4MCU4MTElRTklODAlQjElRTklOTYlOTMlRTQlQkQlQkYlRTMlODElODQlRTUlODAlOTIlRTMlODElOTclRTMlODElQTYlRTUlODglODYlRTMlODElOEIlRTMlODElQTMlRTMlODElOUYlRTYlOUMlQUMlRTUlQkQlOTMlRTMlODElQUUlRTMlODIlQjMlRTMlODIlQjklRTMlODMlOTEmdHh0LWFsaWduPWxlZnQlMkN0b3AmdHh0LWNvbG9yPSUyM0ZGRkZGRiZ0eHQtZm9udD1IaXJhZ2lubyUyMFNhbnMlMjBXNiZ0eHQtc2l6ZT01NiZ0eHQtcGFkPTAmcz02ZGU5ZjQzNWRiNDQzOTNlNDJkZGMzNzkwMTQ4YmRiZQ&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDBzYXRva2VuaWNoaSZ0eHQtY29sb3I9JTIzRkZGRkZGJnR4dC1mb250PUhpcmFnaW5vJTIwU2FucyUyMFc2JnR4dC1zaXplPTM2JnR4dC1wYWQ9MCZzPWIyMWZjYWU0MWM5ODVkODc5YTUwNmU1MWY3YzVmZjZh&blend-x=242&blend-y=480&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&s=d46f42d5bc4e361d1592e92867648c7c)

こんにちは、エンジニアの satokenichi です。最近、AI コーディングアシスタントが話題ですよね。「どれを選べばいいの？」と悩んでいる方も多いのではないでしょうか。私も同じ悩みを抱えていました。そこで、Claude Code と Cursor を実際に使い比べてみることにした...

---

### [AI による自然言語アサーション](https://zenn.dev/mizchi/articles/ai-assertion-with-claude-code)

![AI による自然言語アサーション](https://res.cloudinary.com/zenn/image/upload/s--ny-iubRg--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:AI%2520%25E3%2581%25AB%25E3%2582%2588%25E3%2582%258B%25E8%2587%25AA%25E7%2584%25B6%25E8%25A8%2580%25E8%25AA%259E%25E3%2582%25A2%25E3%2582%25B5%25E3%2583%25BC%25E3%2582%25B7%25E3%2583%25A7%25E3%2583%25B3%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:mizchi%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2liclRHT052Z3d3ay1fNGxlcVk4TGNGSlNuX0FoWnpEWVlKaXJNcWc9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code を初めて使う人向けの実践ガイド](https://zenn.dev/hokuto_tech/articles/86d1edb33da61a)

![Claude Code を初めて使う人向けの実践ガイド](https://res.cloudinary.com/zenn/image/upload/s--rZIv9ZtJ--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%2520%25E3%2582%2592%25E5%2588%259D%25E3%2582%2581%25E3%2581%25A6%25E4%25BD%25BF%25E3%2581%2586%25E4%25BA%25BA%25E5%2590%2591%25E3%2581%2591%25E3%2581%25AE%25E5%25AE%259F%25E8%25B7%25B5%25E3%2582%25AC%25E3%2582%25A4%25E3%2583%2589%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:morizyun%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2M1NWJmMDA5ZmUuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:HOKUTO%2520Tech%2520Blog%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2RjMjQxYzUyM2QuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code を超えたかも！？OpenHands CLI で抽象的な指示から完動するコードを一発生成](https://zenn.dev/minedia/articles/openhands-cli)

![Claude Codeを超えたかも！？OpenHands CLIで抽象的な指示から完動するコードを一発生成](https://res.cloudinary.com/zenn/image/upload/s--eQJJedYi--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2582%2592%25E8%25B6%2585%25E3%2581%2588%25E3%2581%259F%25E3%2581%258B%25E3%2582%2582%25EF%25BC%2581%25EF%25BC%259FOpenHands%2520CLI%25E3%2581%25A7%25E6%258A%25BD%25E8%25B1%25A1%25E7%259A%2584%25E3%2581%25AA%25E6%258C%2587%25E7%25A4%25BA%25E3%2581%258B%25E3%2582%2589%25E5%25AE%258C%25E5%258B%2595%25E3%2581%2599%25E3%2582%258B%25E3%2582%25B3%25E3%2583%25BC%25E3%2583%2589%25E3%2582%2592%25E4%25B8%2580%25E7%2599%25BA%25E7%2594%259F%25E6%2588%2590%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Matsukura%2520Yuki%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzg5ODUyZjZkYzguanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E6%25A0%25AA%25E5%25BC%258F%25E4%25BC%259A%25E7%25A4%25BE%25E3%2583%259E%25E3%2582%25A4%25E3%2583%25B3%25E3%2583%2587%25E3%2582%25A3%25E3%2582%25A2%2520%25E3%2583%2586%25E3%2583%2583%25E3%2582%25AF%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2diQWZWd2dLbmhzWjJZdGgyY2k1c2hveDdQWHl5UUVaN0MyV2JkQ0E9czk2LWM=%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code で効率的に開発するための知見管理](https://zenn.dev/driller/articles/2a23ef94f1d603)

![Claude Codeで効率的に開発するための知見管理](https://res.cloudinary.com/zenn/image/upload/s--2wOPS60P--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25A7%25E5%258A%25B9%25E7%258E%2587%25E7%259A%2584%25E3%2581%25AB%25E9%2596%258B%25E7%2599%25BA%25E3%2581%2599%25E3%2582%258B%25E3%2581%259F%25E3%2582%2581%25E3%2581%25AE%25E7%259F%25A5%25E8%25A6%258B%25E7%25AE%25A1%25E7%2590%2586%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:driller%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2lPT1dLNnlQWE9BNndvZDFlYkxTQ0FLOGlpX1E3X2hqWmVwbDdJeUE9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーの Oikon＠外資 IT エンジニアさん: 「Claude Code のカスタム Slash Command を紹介する： ⚫︎ /bugfix : バグ修正指示用。Web 検索や MCP サーバー使わせて最新情報も使わせる ⚫︎ /explain-project : 最近 OSS を読むこと増えたので、概要を出してもらう ⚫︎ /feature-log : 変更結果のドキュメント化 ⚫︎ /plan-to-checklist : https://t.co/bJvSkC8d8o」 / X](https://x.com/gaishi_narou/status/1935533999218450492)

![XユーザーのOikon＠外資ITエンジニアさん: 「Claude CodeのカスタムSlash Commandを紹介する：   ⚫︎ /bugfix : バグ修正指示用。Web検索やMCPサーバー使わせて最新情報も使わせる  ⚫︎ /explain-project : 最近OSSを読むこと増えたので、概要を出してもらう   ⚫︎ /feature-log : 変更結果のドキュメント化   ⚫︎ /plan-to-checklist : https://t.co/bJvSkC8d8o」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの Oikon＠外資 IT エンジニアさん: 「Claude Code の生産性が 10 倍上がる Tips が、初心者向けにまとまっていて分かりやすかったので共有： 1. Plan + 実行モードの使用（Shift + Tab） 2. CLAUDE .md にワークフローを記述 3. --resume で会話の分岐 4. /clear による Context の初期化 5. Cursor (IDE)内での Claude Code の使用 6.」 / X](https://x.com/gaishi_narou/status/1935522706650439693)

![XユーザーのOikon＠外資ITエンジニアさん: 「Claude Codeの生産性が10倍上がるTipsが、初心者向けにまとまっていて分かりやすかったので共有：   1. Plan + 実行モードの使用（Shift + Tab） 2. CLAUDE .mdにワークフローを記述 3. --resume で会話の分岐 4. /clearによるContextの初期化 5. Cursor (IDE)内でのClaude Codeの使用 6.」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Claude Code どこまでも/ Claude Code Everywhere](https://speakerdeck.com/nwiizo/claude-everywhere)

![Claude Code どこまでも/ Claude Code Everywhere](https://files.speakerdeck.com/presentations/a98a9149370e4a609915000b7660fd60/slide_0.jpg?35509489)

僕が Claude Code に初めて触れたのは、2025 年の春だった。生成 AI にはすでに慣れ親しんでいた。流行に乗り遅れてはいけないと必死に勉強し、エディターの補完機能やコード生成ツールとして日常的に活用していた。ただ、当時の僕にとってそれはまだ「CLI で動く便利なコーディング支援ツール」程度の認識でしか&hellip;

---

### [Claude Code 中級者ガイド](https://zenn.dev/medicalforce/articles/8bc0b6afbbb8a7)

![Claude Code 中級者ガイド](https://res.cloudinary.com/zenn/image/upload/s--N-si0FdW--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%2520%25E4%25B8%25AD%25E7%25B4%259A%25E8%2580%2585%25E3%2582%25AC%25E3%2582%25A4%25E3%2583%2589%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Gatsby%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzkyZjY0YWIzNTQuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E3%2583%25A1%25E3%2583%2587%25E3%2582%25A3%25E3%2582%25AB%25E3%2583%25AB%25E3%2583%2595%25E3%2582%25A9%25E3%2583%25BC%25E3%2582%25B9%2520%25E3%2583%2586%25E3%2583%2583%25E3%2582%25AF%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzM1ZTFmODJkNzIuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーのぬこぬこさん: 「Claude Code がリモート MCP に対応 これまでローカル MCP にのみ対応していたが、ベンダーの公式提供された URL を追加するだけで MCP 対応できるように。OAuth 対応により安全に認証することができる。 https://t.co/OtpxzjJJCI」 / X](https://x.com/schroneko/status/1935460134756696572)

![Xユーザーのぬこぬこさん: 「Claude Code がリモート MCP に対応  これまでローカル MCP にのみ対応していたが、ベンダーの公式提供された URL を追加するだけで MCP 対応できるように。OAuth 対応により安全に認証することができる。 https://t.co/OtpxzjJJCI」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーの ICHI💻 生成 AI 活用さん: 「🚨 Cursor がついに月額$200 の Ultra Plan をリリース！ Pro プランの 20 倍の使用量でパワーユーザーの要望に応答 注目ポイント： • OpenAI/Anthropic/Google/xAI との長期契約で実現 • Pro プランも無制限・レート制限付きに進化 詳細 👇 https://t.co/OplvwO8XQ4 #Cursor #AI 開発 #生成 AI」 / X](https://x.com/kronos_engineer/status/1934940698241056836)

![XユーザーのICHI💻生成AI活用さん: 「🚨 Cursorがついに月額$200のUltra Planをリリース！  Proプランの20倍の使用量でパワーユーザーの要望に応答  注目ポイント： • OpenAI/Anthropic/Google/xAIとの長期契約で実現 • Proプランも無制限・レート制限付きに進化  詳細👇 https://t.co/OplvwO8XQ4  #Cursor #AI開発 #生成AI」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Claude Code で実用的な Web サービスを作る｜ himara2](https://note.com/himaratsu/n/nddf0efa67d42)

![Claude Codeで実用的なWebサービスを作る｜himara2](https://assets.st-note.com/production/uploads/images/196694012/rectangle_large_type_2_76e170fc96d4fddf75c9d615478cc01d.png?fit=bounds&quality=85&width=1280)

こんにちは！ひまらつ（@himara2）です。 Claude Code が話題ですね。実際に使ってみると Cline や Cursor などの AI エージェントと比べて賢さのレベルが高く、開発アシスタントとして次のレベルに来ているような気がします。 サンプルアプリやプロトタイプを作れるのは確実なので、今回はデータベースを持つ実用的なアプリケーションをどれくらい作れるか試してみました。これから Claude Code を触る方のヒントとなれば幸いです:) 今回作ったもの 麻雀点棒管理アプリを作った 麻雀をするときに点数の管理をする Web アプリです。 定期的に友人と麻雀をしてるんですが、友人宅にあ

---

### [X ユーザーの西見 公宏 | Generative Agents さん: 「昨日「ブラウザ版 Cursor ですよ」と教えてもらった Dia Browser が凄まじい。 ある意味エディタに LLM を組み込んだ『だけ』な Cursor などのエディタがあれほど便利になるのだから、ブラウザと組み合わせたらどうなるかは、推して知るべしだった。 ここにエージェントが組み合わさる、と。。」 / X](https://x.com/mah_lab/status/1938789289070076245)

![Xユーザーの西見 公宏 | Generative Agentsさん: 「昨日「ブラウザ版Cursorですよ」と教えてもらったDia Browserが凄まじい。  ある意味エディタにLLMを組み込んだ『だけ』なCursorなどのエディタがあれほど便利になるのだから、ブラウザと組み合わせたらどうなるかは、推して知るべしだった。  ここにエージェントが組み合わさる、と。。」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [o3 MCP で Claude Code が最強の検索力を手に入れた](https://zenn.dev/yoshiko/articles/claude-code-with-o3)

![o3 MCPでClaude Codeが最強の検索力を手に入れた](https://res.cloudinary.com/zenn/image/upload/s--xAYvgHwM--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:o3%2520MCP%25E3%2581%25A7Claude%2520Code%25E3%2581%258C%25E6%259C%2580%25E5%25BC%25B7%25E3%2581%25AE%25E6%25A4%259C%25E7%25B4%25A2%25E5%258A%259B%25E3%2582%2592%25E6%2589%258B%25E3%2581%25AB%25E5%2585%25A5%25E3%2582%258C%25E3%2581%259F%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2582%2588%25E3%2581%2597%25E3%2581%2593%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2kwU3JDUjBpVERyUHpqWnF4YjJLZ0tueHgtamE0N253SEE0NGE4RDhrPXMyNTAtYw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code にコマンド一発で MCP サーバを簡単設定](https://zenn.dev/karaage0703/articles/3bd2957807f311)

![Claude Codeにコマンド一発でMCPサーバを簡単設定](https://res.cloudinary.com/zenn/image/upload/s--qFEpkSVb--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AB%25E3%2582%25B3%25E3%2583%259E%25E3%2583%25B3%25E3%2583%2589%25E4%25B8%2580%25E7%2599%25BA%25E3%2581%25A7MCP%25E3%2582%25B5%25E3%2583%25BC%25E3%2583%2590%25E3%2582%2592%25E7%25B0%25A1%25E5%258D%2598%25E8%25A8%25AD%25E5%25AE%259A%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%258B%25E3%2582%2589%25E3%2581%2582%25E3%2581%2592%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2hDZEtvakJfZXdDTjNCV1Z0WXIteFNIZ0hmRjlXZmt3QzI5c0Y0aXYwPXMyNTAtYw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーの Takuto Wada さん: 「なるほど、TDD やテスト駆動開発という言葉は広まりすぎて「意味の希薄化」が発生し、曖昧な理解のまま自動テストやテストファーストと混同され、それが LLM の学習データにも影響したが、人名を与えると LLM に「具体的な参照点」を与え、より具体的なプログラミングスタイルに限定させる効果があったのか https://t.co/p6SCPj8YdA」 / X](https://x.com/t_wada/status/1937712692091048391)

![XユーザーのTakuto Wadaさん: 「なるほど、TDDやテスト駆動開発という言葉は広まりすぎて「意味の希薄化」が発生し、曖昧な理解のまま自動テストやテストファーストと混同され、それがLLMの学習データにも影響したが、人名を与えるとLLMに「具体的な参照点」を与え、より具体的なプログラミングスタイルに限定させる効果があったのか https://t.co/p6SCPj8YdA」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [React Ink によるリッチ CLI (ClaudeCode の裏側のアレ)](https://zenn.dev/mizchi/articles/react-ink-renderer-for-ai-age)

![React Ink によるリッチ CLI (ClaudeCodeの裏側のアレ)](https://res.cloudinary.com/zenn/image/upload/s--TqgL-vNL--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:React%2520Ink%2520%25E3%2581%25AB%25E3%2582%2588%25E3%2582%258B%25E3%2583%25AA%25E3%2583%2583%25E3%2583%2581%2520CLI%2520%2528ClaudeCode%25E3%2581%25AE%25E8%25A3%258F%25E5%2581%25B4%25E3%2581%25AE%25E3%2582%25A2%25E3%2583%25AC%2529%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:mizchi%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2liclRHT052Z3d3ay1fNGxlcVk4TGNGSlNuX0FoWnpEWVlKaXJNcWc9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Mastra + Ollama + MCP でローカル AI エージェントを作る](https://zenn.dev/robustonian/articles/mastra_ollama_mcp)

![Mastra + Ollama + MCPでローカルAIエージェントを作る](https://res.cloudinary.com/zenn/image/upload/s--BLvzFIhH--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Mastra%2520%252B%2520Ollama%2520%252B%2520MCP%25E3%2581%25A7%25E3%2583%25AD%25E3%2583%25BC%25E3%2582%25AB%25E3%2583%25ABAI%25E3%2582%25A8%25E3%2583%25BC%25E3%2582%25B8%25E3%2582%25A7%25E3%2583%25B3%25E3%2583%2588%25E3%2582%2592%25E4%25BD%259C%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E9%2587%2591%25E3%2581%25AE%25E3%2583%258B%25E3%2583%25AF%25E3%2583%2588%25E3%2583%25AA%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzQ1NmVjZjczNWIuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Gemini CLI のサンドボックス機能とは - Algomatic Tech Blog](https://tech.algomatic.jp/entry/2025/06/26/055948)

![Gemini CLI のサンドボックス機能とは - Algomatic Tech Blog](https://cdn.image.st-hatena.com/image/scale/255a15932fc19bc4bf46fdd77ad4a99d8176342e/backend=imagemagick;version=1;width=1300/https%3A%2F%2Fcdn-ak.f.st-hatena.com%2Fimages%2Ffotolife%2Fy%2Fyasu_wakamenori%2F20250626%2F20250626054737.jpg)

はじめに Google から Gemini をコマンドラインで対話的に利用できる「Gemini CLI」が登場しましたね！ 基本的な使い方については、すでに多くの方が素晴らしい解説記事を公開されていますので、ぜひそちらもご覧ください。 参考 zenn.dev この記事では、Gemini CLI が備える機能の中でも、Claude Code にはない「サンドボックス」機能に焦点を当てます。 リポジトリはこちら github.com この記事でわかること Gemini CLI のサンドボックス機能がなぜ必要なのか サンドボックスが有効になると、具体的に何が起きるのか -s フラグを付けるだけの簡単な使い方 ma…

---

### [Gemini CLI を会社で使う場合のプラン選択方針](https://zenn.dev/hololab/articles/geminicli-001-75046b80817049)

![Gemini CLIを会社で使う場合のプラン選択方針](https://res.cloudinary.com/zenn/image/upload/s--ftLqIlaB--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Gemini%2520CLI%25E3%2582%2592%25E4%25BC%259A%25E7%25A4%25BE%25E3%2581%25A7%25E4%25BD%25BF%25E3%2581%2586%25E5%25A0%25B4%25E5%2590%2588%25E3%2581%25AE%25E3%2583%2597%25E3%2583%25A9%25E3%2583%25B3%25E9%2581%25B8%25E6%258A%259E%25E6%2596%25B9%25E9%2587%259D%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:%25E4%25B8%25AD%25E6%259D%2591%2520%25E8%2596%25AB%2520%252F%2520%25E3%2583%259B%25E3%2583%25AD%25E3%2583%25A9%25E3%2583%259C%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2RkMzA4MzIwZTkuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:%25E3%2583%259B%25E3%2583%25AD%25E3%2583%25A9%25E3%2583%259C%25E3%2581%25AE%25E3%2583%2586%25E3%2583%2583%25E3%2582%25AF%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2c2V1JMM1hOTEM5ZWdzSW0wbG9xQUhCUmJWbkJ1M3JocGpIZzVsZ3c9czI1MC1j%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [Anthropic の Desktop Extensions (DXT) を試す｜ npaka](https://note.com/npaka/n/nb206aa63ac7e)

![Anthropic の Desktop Extensions (DXT) を試す｜npaka](https://assets.st-note.com/production/uploads/images/198630065/rectangle_large_type_2_fa2e4588277988cbe780f1beec404b20.png?fit=bounds&quality=85&width=1280)

「Anthropic」の「Desktop Extensions」 (DXT) を試したのでまとめました。 1. Desktop Extensions (DXT) 「Desktop Extensions (DXT)」は、ワンクリックで手軽に「ローカル MCP サーバ」を PC にインストールできるファイル形式 (.dxt) です。「ローカル MCP サーバ」と、その機能を説明する「manifest.json」を zip アーカイブでまとめたｍので、現在は「Claude Desktop」(Mac/Windows 用)でのみ利用できます。 2. DXT の作成 過去に作成した、シンプルな米国

---

### [X ユーザーの田中義弘 | taziku CEO / AI × Creative さん: 「直接 3D 化するの、もうやめよう。 RGB 画像 →3D は精度に限界がある。だから Hi3DGen は法線マップを挟む。 法線マップを中間生成し活用することで、画像から高忠実度の 3D ジオメトリを生成する新しいフレームワーク。詳細は 🧵 から https://t.co/NTz85FV4F2」 / X](https://x.com/taziku_co/status/1938085605948465441)

![Xユーザーの田中義弘 | taziku CEO / AI × Creativeさん: 「直接3D化するの、もうやめよう。  RGB画像→3Dは精度に限界がある。だからHi3DGenは法線マップを挟む。  法線マップを中間生成し活用することで、画像から高忠実度の3Dジオメトリを生成する新しいフレームワーク。詳細は🧵から https://t.co/NTz85FV4F2」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [【無料公開】Google の新 AI エージェント「Gemini CLI」登場！使い方と基本機能を速報解説｜ ChatGPT 研究所](https://chatgpt-lab.com/n/n4ccc9d035cab)

![【無料公開】Googleの新AIエージェント「Gemini CLI」登場！使い方と基本機能を速報解説｜ChatGPT研究所](https://assets.st-note.com/production/uploads/images/198366199/rectangle_large_type_2_6da2e9ddffbbc5b89319d727df3c3792.png?fit=bounds&quality=85&width=1280)

2025 年 6 月 25 日、Google からオープンソースの AI エージェント「Gemini CLI」が発表されました。 本記事では、Gemini CLI のインストール方法から具体的な使い方まで、要点を押さえて解説します。 要点： Gemini CLI が公開: ターミナルから直接 Gemini 2.5 Pro が使える、オープンソースの AI エージェント。 無料でほぼ無制限: 個人の Google アカウントなら、1 分あたり 60 リクエスト、1 日 1,000 リクエストまで無料で利用可能 強力なツール連携: ファイル操作、Web 検索、コマンド実行などを、AI が状況に応じて自動で実行。`@

---

### [Gemini CLI 利用時の認証方法別プライバシーポリシー](https://zenn.dev/nuits_jp/articles/2025-06-26-gemini-cli-privacy-policy)

![Gemini CLI利用時の認証方法別プライバシーポリシー](https://res.cloudinary.com/zenn/image/upload/s--avTCJV6G--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Gemini%2520CLI%25E5%2588%25A9%25E7%2594%25A8%25E6%2599%2582%25E3%2581%25AE%25E8%25AA%258D%25E8%25A8%25BC%25E6%2596%25B9%25E6%25B3%2595%25E5%2588%25A5%25E3%2583%2597%25E3%2583%25A9%25E3%2582%25A4%25E3%2583%2590%25E3%2582%25B7%25E3%2583%25BC%25E3%2583%259D%25E3%2583%25AA%25E3%2582%25B7%25E3%2583%25BC%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Atsushi%2520Nakamura%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2kxcWVVUGV3Z1lrYXhhaE1uWW1rQnRRT0RVLWtNemJiMEhfTHo4MkE9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Anthropic の Desktop Extensions (DXT)完全ガイド： ローカル AI アプリケーションの新時代](https://zenn.dev/cadp/articles/6d9dd374fd3d32)

![AnthropicのDesktop Extensions (DXT)完全ガイド： ローカルAIアプリケーションの新時代](https://res.cloudinary.com/zenn/image/upload/s--ETLxFCG7--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Anthropic%25E3%2581%25AEDesktop%2520Extensions%2520%2528DXT%2529%25E5%25AE%258C%25E5%2585%25A8%25E3%2582%25AC%25E3%2582%25A4%25E3%2583%2589%25EF%25BC%259A%2520%25E3%2583%25AD%25E3%2583%25BC%25E3%2582%25AB%25E3%2583%25ABAI%25E3%2582%25A2%25E3%2583%2597%25E3%2583%25AA%25E3%2582%25B1%25E3%2583%25BC%25E3%2582%25B7%25E3%2583%25A7%25E3%2583%25B3%25E3%2581%25AE%25E6%2596%25B0%25E6%2599%2582%25E4%25BB%25A3%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:Gunther%2520Brunner%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzhjMjJkNjJjOGUuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:CyberAgent%2520Developer%2520...%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2lCOWhzUlhhNW5lUXlhNF81U2RyRnNDUWkxcll3WDB4RTlDRjB4eGc9czk2LWM=%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [怖くない！ はじめての Claude Code](https://speakerdeck.com/ks0318/bu-kunai-hazimetenoclaude-code)

![怖くない！ はじめてのClaude Code](https://files.speakerdeck.com/presentations/b5a285e93fca423398d78228a625a270/slide_0.jpg?35599187)

---

### [Agentic Workflow という選択肢を考える](https://speakerdeck.com/tkikuchi1002/agentic-workflowtoiuxuan-ze-zhi-wokao-eru)

![Agentic Workflowという選択肢を考える](https://files.speakerdeck.com/presentations/ab19a1633bca461b90b1835115c792e7/slide_0.jpg?35588855)

2025-06-24 AI エージェント開発 Night での LT 資料です。

---

### [「AI に代替されない」エンジニアになる 3 つの能力 ──“日報”で鍛える問題解決力](https://codezine.jp/article/detail/21313)

![「AIに代替されない」エンジニアになる3つの能力──“日報”で鍛える問題解決力](https://codezine.jp/static/images/article/21313/21313_ogp.jpg)

ChatGPT の台頭以降、IT エンジニアの役割は日々変わりつつある。将来的 AI 時代を生き抜くエンジニアの成長法とは ──‟日報‟の活用で「本質的な価値」を向上な AGI（汎用人工知能）と ASI（人工超知能）の発現も予想される中、自分自身のポジションを確保し、キャリアを築く方法に悩むエンジニアは少なくない。プライベートを犠牲にして新言語の習得や新技術の勉強を行うエンジニアも存在するなか、「休みの時間に猛勉強するようなことをしなくても、日々の仕事をちゃんとやっていくことで十分な成長が得られる」と語るのが、合同会社 HaveFunTech で代表社員を務め、株式会社リンケージでは CTO 兼 COO の職責を担う曽根壮大氏だ。日々の業務を通してエンジニアとしての能力を伸ばし、AI 時代を生き残るために必要な行動や考え方について、曽根氏が講演を行った。

---

### [MCP サーバーを使うなら Prompt Caching が大切だと思い知った話](https://zenn.dev/ncdc/articles/26165a6fedd7e4)

![MCPサーバーを使うなら Prompt Caching が大切だと思い知った話](https://res.cloudinary.com/zenn/image/upload/s--k1qm6e_h--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:MCP%25E3%2582%25B5%25E3%2583%25BC%25E3%2583%2590%25E3%2583%25BC%25E3%2582%2592%25E4%25BD%25BF%25E3%2581%2586%25E3%2581%25AA%25E3%2582%2589%2520Prompt%2520Caching%2520%25E3%2581%258C%25E5%25A4%25A7%25E5%2588%2587%25E3%2581%25A0%25E3%2581%25A8%25E6%2580%259D%25E3%2581%2584%25E7%259F%25A5%25E3%2581%25A3%25E3%2581%259F%25E8%25A9%25B1%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:%25E3%2581%2584%25E3%2581%25B0%25E3%2582%2589%25E3%2581%258D%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzNhODZhNDA5ZDMuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/g_south_west%2Ch_34%2Cl_default:og-publication-pro-mark-xcosax%2Cw_34%2Cx_217%2Cy_158/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:NCDC%25E3%2582%25A8%25E3%2583%25B3%25E3%2582%25B8%25E3%2583%258B%25E3%2582%25A2%25E3%2583%2596%25E3%2583%25AD%25E3%2582%25B0%2Cx_255%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2lXRjZXeUJCMTBrRDZNaV9Fa0tLQi13WFJSUC04eFlJbDV5eWljPXM5Ni1j%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [API Key 無しで Gemini をセキュアに Google Apps Script から利用する - エムスリーテックブログ](https://www.m3tech.blog/entry/gemini-gas)

![API Key 無しで Gemini をセキュアに Google Apps Script から利用する  - エムスリーテックブログ](https://cdn.image.st-hatena.com/image/scale/9d23037aa7d7f2ecdb4e87f2172747c75e9bae71/backend=imagemagick;version=1;width=1300/https%3A%2F%2Fcdn-ak.f.st-hatena.com%2Fimages%2Ffotolife%2Fm%2Fm3tech%2F20250624%2F20250624193511.png)

本文に関係ないドッグランに行ったときの犬たち こんにちは、AI・機械学習チームの山本（@hiro_o918）です。 このブログは AI・機械学習チームブログリレー 5 日目の記事です。 これまでのリレー記事でも出てきたように、弊社でも AI を活用したプロダクト開発が進んでいます。 それに加えてビジネスサイドでも AI 活用が進んでおり、OSS 版 Dify を導入・運用したり、Google Workspace に付帯する Gemini を活用したりしています。 このような状況から、AI 機能の実装に関してビジネスサイドから相談を受ける機会が多いのですが、その際には利便性だけでなくセキュリティ…

---

### [X ユーザーの mizchi さん: 「gemini-cli が OSS なので、 gemini-cli 自体に読ませている https://t.co/LL7rpr9lVk」 / X](https://x.com/mizchi/status/1937865486701850716)

![Xユーザーのmizchiさん: 「gemini-cli がOSSなので、 gemini-cli 自体に読ませている https://t.co/LL7rpr9lVk」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーのぬこぬこさん: 「Gemini CLI の README をよく見たら、MCP 経由で画像や動画、音声生成も繋げられるので、素材をその場で生成して、そのままウェブサービスに組み込めるのか https://t.co/ntZDaJac9R」 / X](https://x.com/schroneko/status/1937873442952597513)

![Xユーザーのぬこぬこさん: 「Gemini CLI の README をよく見たら、MCP 経由で画像や動画、音声生成も繋げられるので、素材をその場で生成して、そのままウェブサービスに組み込めるのか https://t.co/ntZDaJac9R」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Gemini CLI 入門 (2) - クイックスタート｜ npaka](https://note.com/npaka/n/n36f1968dda9b?sub_rt=share_pw)

![Gemini CLI 入門 (2) - クイックスタート｜npaka](https://assets.st-note.com/production/uploads/images/198316569/rectangle_large_type_2_80fefcc80653d7fea3c25390737aa825.png?fit=bounds&quality=85&width=1280)

「Gemini CLI」を試したのでまとめました。 前回

1.  Gemini CLI 「Gemini CLI」は、「Gemini」のパワーをターミナルに直接提供するオープンソースの AI エージェントです。 次のことが可能になります。 ・「Gemini」の 100 万トークンのコンテキストウィンドウ内外で、大規模なコードベースのクエリと編集が可能。 ・「Gemini」のマルチモーダル機能を使用して、PDF やスケッチから新しいアプリを生成。 ・プルリクエストのクエリや複雑なリベースの処理などの運用タスクを自動化。 ・ツールと MCP サーバを使用して、「Medmeia generat

---

### [gemini-cli の google_web_search が最高](https://zenn.dev/mizchi/articles/gemini-cli-for-google-search)

![gemini-cli の google_web_search が最高](https://res.cloudinary.com/zenn/image/upload/s--nV5AGtPy--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:gemini-cli%2520%25E3%2581%25AE%2520google_web_search%2520%25E3%2581%258C%25E6%259C%2580%25E9%25AB%2598%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:mizchi%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2liclRHT052Z3d3ay1fNGxlcVk4TGNGSlNuX0FoWnpEWVlKaXJNcWc9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Gemini CLI の簡単チュートリアル](https://zenn.dev/schroneko/articles/gemini-cli-tutorial)

![Gemini CLI の簡単チュートリアル](https://res.cloudinary.com/zenn/image/upload/s--_yGIl0h0--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Gemini%2520CLI%2520%25E3%2581%25AE%25E7%25B0%25A1%25E5%258D%2598%25E3%2583%2581%25E3%2583%25A5%25E3%2583%25BC%25E3%2583%2588%25E3%2583%25AA%25E3%2582%25A2%25E3%2583%25AB%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%25AC%25E3%2581%2593%25E3%2581%25AC%25E3%2581%2593%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzE4ZDE4NWExYTYuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [MCP のジレンマと、A2A への期待｜ takuya kikuch | Algomatic](https://note.com/takuyakikuchi/n/n4051ca6a7f92?sub_rt=share_pb)

![MCPのジレンマと、A2Aへの期待｜takuya kikuch | Algomatic](https://assets.st-note.com/production/uploads/images/198270027/rectangle_large_type_2_9ecb425edaf963bdba5a019b9b8fdd1d.png?fit=bounds&quality=85&width=1280)

こんにちは、Algomatic でネオセールスカンパニーの CTO をしているきくち(@\_pochi)です。ネオセールスカンパニーでは、営業 AI エージェント「アポドリ」を開発・提供中です。

アポドリ | 人を増やさず営業成果を上げる営業 AI エージェント

営業 AI エージェント「アポドリ」は、狙いたい企業リストを渡すだけで商談獲得までの負荷の高い業務を人に変わって丸ごと遂行する

apodori.ai

先日登壇させていただいた、「AI エージェント開発 Night」の座談会で「インターフェースとしてのエージェントについてどう思う？」というお題がありまして、「ワクワクしますよ

---

### [Google がインターネット接続不要でローカル動作する高性能ロボット AI モデル「Gemini Robotics On-Device」を発表](https://gigazine.net/news/20250625-gemini-robotics-on-device/?utm_source=x&utm_medium=sns&utm_campaign=x_post&utm_content=20250625-gemini-robotics-on-device)

![Googleがインターネット接続不要でローカル動作する高性能ロボットAIモデル「Gemini Robotics On-Device」を発表](https://i.gzn.jp/img/2025/06/25/gemini-robotics-on-device/00.png)

Google がロボット向けの VLA モデル「Gemini Robotics On-Device」を 2025 年 6 月 24 日に発表しました。Gemini Robotics On-Device はローカルの GPU を用いて処理可能な軽量さを特徴としており、既存のローカル VLA モデルと比べて高い性能を備えています。

---

### [Claude Code の .claude/commands/\*\*.md は設定した方がいい - じゃあ、おうちで学べる](https://syu-m-5151.hatenablog.com/entry/2025/06/25/062736)

![Claude Code の .claude/commands/**.md は設定した方がいい - じゃあ、おうちで学べる](https://ogimage.blog.st-hatena.com/8454420450094081900/6802418398487300151/1750929310)

はじめに Claude Code でよく同じコメントを打ってませんか？ 「毎回『テスト実行して、lint チェックして、問題なければコミットして』って言うの面倒だな」とか「プロジェクトごとに決まった手順があるんだけど、毎回説明するのダルい」とか思ったことないですか？ そんなあなたに朗報です。 Claude Code にはカスタムスラッシュコマンドという機能があって、よく使うプロンプトをコマンド化できるんです。しかも設定は超簡単。Markdown ファイルを置くだけ。手順書や Makefile が自然言語で書ける時代ですね ⋯。 docs.anthropic.com 正直なところ、この機能を知ったときは…

---

### [X ユーザーの CodeRabbit (JP)さん: 「#CodeRabbit が各種 AI コーディングツールのガイドラインに対応しました 🎉🎉🎉 デフォルトで、以下に対応しています - .cursorrules - .github/copilot-instructions.md - https://t.co/ynFU5uiKDA - .cursor/rules/ - .windsurfrules - .clinerules - .rules/ 設定は管理画面、または」 / X](https://x.com/Coderabbitaija/status/1937723057373909320)

![XユーザーのCodeRabbit (JP)さん: 「#CodeRabbit が各種AIコーディングツールのガイドラインに対応しました🎉🎉🎉  デフォルトで、以下に対応しています  - .cursorrules - .github/copilot-instructions.md - https://t.co/ynFU5uiKDA - .cursor/rules/ - .windsurfrules - .clinerules - .rules/  設定は管理画面、または」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Google Cloud が A2A を Linux Foundation に移管｜ npaka](https://note.com/npaka/n/n70af0f94b7be)

![Google Cloud が A2A を Linux Foundation に移管｜npaka](https://assets.st-note.com/production/uploads/images/198224877/rectangle_large_type_2_613fec0c251122325ad25d88f4969f58.jpeg?fit=bounds&quality=85&width=1280)

以下の記事が面白かったので、簡単にまとめました。 ・Google Cloud donates A2A to Linux Foundation 1. Google Cloud が A2A を Linux Foundation に移管 本日 (6 月 23 日)、「Linux Foundation」は「Open Source Summit North America」において、「Amazon Web Services」「Cisco」「Google」「Microsoft」「Salesforce」「SAP」「ServiceNow」と共同で「Agent2Agent プロジェクト」を立ち上げる

---

### [Google DeepMind、ロボットを完全ローカルで動かせる AI モデル「Gemini Robotics On-Device」を初期リリース](https://www.itmedia.co.jp/aiplus/articles/2506/25/news056.html#utm_term=share_sp)

![Google DeepMind、ロボットを完全ローカルで動かせるAIモデル「Gemini Robotics On-Device」を初期リリース](https://image.itmedia.co.jp/aiplus/articles/2506/25/cover_news056.jpg)

Google DeepMind は、ロボット上で完全にローカル実行できる AI モデル「Gemini Robotics On-Device」を初期リリースした。ネットワーク接続に依存せず低遅延で動作するため、オフライン環境でのロボット活用が期待される。

---

### [Claude Code コマンドチートシート完全ガイド - Qiita](https://qiita.com/akira_papa_AI/items/d68782fbf03ffd9b2f43?utm_campaign=post_article&utm_medium=twitter&utm_source=twitter_share)

![Claude Code コマンドチートシート完全ガイド - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Farticle-ogp-background-afbab5eb44e0b055cce1258705637a91.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1pbWFnZS1zdG9yZSUyRjAlMkY0MzUyMzMlMkYzYWVhMjJjODY0NGRjN2RhNzNhYmNiZWViNzNiMzQ5NTY1ZjFhYzg3JTJGeF9sYXJnZS5wbmclM0YxNzQzODkzNzQwP2l4bGliPXJiLTQuMC4wJmFyPTElM0ExJmZpdD1jcm9wJm1hc2s9ZWxsaXBzZSZiZz1GRkZGRkYmZm09cG5nMzImcz0zYzAxZGY0NTQwNDA3MDkxOWU4ZDc1YjJmMGMwODg1MQ%26blend-x%3D120%26blend-y%3D467%26blend-w%3D82%26blend-h%3D82%26blend-mode%3Dnormal%26s%3D57d66a48ec5d58fdc4e5256f39ac787a?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9Q2xhdWRlJTIwQ29kZSUyMCVFMyU4MiVCMyVFMyU4MyU5RSVFMyU4MyVCMyVFMyU4MyU4OSVFMyU4MyU4MSVFMyU4MyVCQyVFMyU4MyU4OCVFMyU4MiVCNyVFMyU4MyVCQyVFMyU4MyU4OCVFNSVBRSU4QyVFNSU4NSVBOCVFMyU4MiVBQyVFMyU4MiVBNCVFMyU4MyU4OSZ0eHQtYWxpZ249bGVmdCUyQ3RvcCZ0eHQtY29sb3I9JTIzMUUyMTIxJnR4dC1mb250PUhpcmFnaW5vJTIwU2FucyUyMFc2JnR4dC1zaXplPTU2JnR4dC1wYWQ9MCZzPWIxZjA4NTQ0MmUyMmJiMGMzMjkxMjdmMzQ4MTM5NTQ0&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDBha2lyYV9wYXBhX0FJJnR4dC1jb2xvcj0lMjMxRTIxMjEmdHh0LWZvbnQ9SGlyYWdpbm8lMjBTYW5zJTIwVzYmdHh0LXNpemU9MzYmdHh0LXBhZD0wJnM9Njg4MDRmOGExYzc3N2U4YTc5ZDg2NzcxYzljNzViN2U&blend-x=242&blend-y=480&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&s=50873a975fd3e79e25a1f559a17633b1)

Claude Code とは Claude Code v1.0.31 は、AI アシスタント Claude をコマンドライン上で活用できるツールです。コードベースの質問、ファイル編集、コマンド実行などを対話的に行うことができます。 重要な注意点: Claude の応答は必ず確認して...

---

### [コードの 90%を AI が書く世界で何が待っているのか / What awaits us in a world where 90% of the code is written by AI](https://speakerdeck.com/rkaga/what-awaits-us-in-a-world-where-90-percent-of-the-code-is-written-by-ai)

![コードの90%をAIが書く世界で何が待っているのか / What awaits us in a world where 90% of the code is written by AI](https://files.speakerdeck.com/presentations/2d064ae570914bec8eb1201dd293a0dd/slide_0.jpg?35569884)

2025/6/24 に開催された「AI 駆動開発、そのやり方で合ってる？PM とエンジニアで語る AI 駆動開発に求められる品質とは」の登壇資料です。
https://offers-jp.connpass.com/event/356194/

---

### [Claude Code と playwright mcp を連携させると開発体験が向上するのでみんなやろう](https://zenn.dev/sesere/articles/4c0b55102dcc84)

![Claude Codeとplaywright mcpを連携させると開発体験が向上するのでみんなやろう](https://res.cloudinary.com/zenn/image/upload/s--c9BKusXK--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25A8playwright%2520mcp%25E3%2582%2592%25E9%2580%25A3%25E6%2590%25BA%25E3%2581%2595%25E3%2581%259B%25E3%2582%258B%25E3%2581%25A8%25E9%2596%258B%25E7%2599%25BA%25E4%25BD%2593%25E9%25A8%2593%25E3%2581%258C%25E5%2590%2591%25E4%25B8%258A%25E3%2581%2599%25E3%2582%258B%25E3%2581%25AE%25E3%2581%25A7%25E3%2581%25BF%25E3%2582%2593%25E3%2581%25AA%25E3%2582%2584%25E3%2582%258D%25E3%2581%2586%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:sesere%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzg4NjY3ZDcwMjMuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [X ユーザーの Taiyo | AI で遊ぶ大学生さん: 「Cursor に Claude Code 拡張機能を入れたら、デバックが超絶楽になった件。 Cmd + ⌥ + K（Mac）／Alt + Ctrl + K（Win/Linux） で参照したいファイルを挿入 → そのまま /bug で AI にバグ修正依頼。 これだけで爆速になるぞ！！！！ https://t.co/ftfKUuHSCL」 / X](https://x.com/taiyo_ai_gakuse/status/1937085314511913056)

![XユーザーのTaiyo | AIで遊ぶ大学生さん: 「CursorにClaude Code拡張機能を入れたら、デバックが超絶楽になった件。  Cmd + ⌥ + K（Mac）／Alt + Ctrl + K（Win/Linux） で参照したいファイルを挿入 → そのまま /bug でAIにバグ修正依頼。  これだけで爆速になるぞ！！！！ https://t.co/ftfKUuHSCL」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [DaVinci Resolve 入門 (2) - 変形とダイナミックズーム｜ npaka](https://note.com/npaka/n/n1ca1663ffe62)

![DaVinci Resolve 入門 (2) - 変形とダイナミックズーム｜npaka](https://assets.st-note.com/production/uploads/images/197984581/rectangle_large_type_2_4ffb4479ce1660af5bc51d2168ad6db0.png?fit=bounds&quality=85&width=1280)

「DaVinci Resolve」の「変形」と「ダイナミックズーム」についてまとめました。 ・DaVinci Resolve v20 前回

1.  変形 「変形」は、クリップの位置、拡大縮小、回転などを操作できる機能です。 (1) クリップを選択し、インスペクタを開き、「カメラ」の「変形」を編集。 ・ズーム (XY) ・位置 (XY) ・回転の角度 ・アンカーポイント (XY) ・ピッチ ・ヨー ・反転 (上下・左右) (2) プレビュー左下で「ダイナミックズーム」を選択。 ハンドルでクリップの位置、拡大縮小、回転を直接操作できます。 (3) 変形アニメーショ

---

### [Claude Code の前と後。やり始めたこととやめたこと](https://zenn.dev/ks0318/articles/0779b38a023896)

![Claude Codeの前と後。やり始めたこととやめたこと](https://res.cloudinary.com/zenn/image/upload/s--tQlyPJpU--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AE%25E5%2589%258D%25E3%2581%25A8%25E5%25BE%258C%25E3%2580%2582%25E3%2582%2584%25E3%2582%258A%25E5%25A7%258B%25E3%2582%2581%25E3%2581%259F%25E3%2581%2593%25E3%2581%25A8%25E3%2581%25A8%25E3%2582%2584%25E3%2582%2581%25E3%2581%259F%25E3%2581%2593%25E3%2581%25A8%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E3%2581%2597%25E3%2581%25B0%25E7%2594%25B0%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzlhMWM5YWI5NTkuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code 時代のアプリ開発手法](https://zenn.dev/itome/articles/f8f1d6ff662a92)

![Claude Code時代のアプリ開発手法](https://res.cloudinary.com/zenn/image/upload/s--C7nMaLxi--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E6%2599%2582%25E4%25BB%25A3%25E3%2581%25AE%25E3%2582%25A2%25E3%2583%2597%25E3%2583%25AA%25E9%2596%258B%25E7%2599%25BA%25E6%2589%258B%25E6%25B3%2595%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Takeshi%2520Tsukamoto%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2NmMDM0ODM0YzMuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code 版 Orchestaror で複雑なタスクをステップ実行する](https://zenn.dev/mizchi/articles/claude-code-orchestrator)

![Claude Code 版 Orchestaror で複雑なタスクをステップ実行する](https://res.cloudinary.com/zenn/image/upload/s--CmPGRWTS--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%2520%25E7%2589%2588%2520Orchestaror%2520%25E3%2581%25A7%25E8%25A4%2587%25E9%259B%2591%25E3%2581%25AA%25E3%2582%25BF%25E3%2582%25B9%25E3%2582%25AF%25E3%2582%2592%25E3%2582%25B9%25E3%2583%2586%25E3%2583%2583%25E3%2583%2597%25E5%25AE%259F%25E8%25A1%258C%25E3%2581%2599%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:mizchi%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2liclRHT052Z3d3ay1fNGxlcVk4TGNGSlNuX0FoWnpEWVlKaXJNcWc9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code: Best Practices and Pro Tips](https://htdocs.dev/posts/claude-code-best-practices-and-pro-tips/)

![Claude Code: Best Practices and Pro Tips](https://htdocs.dev/posts/claude-code-best-practices-and-pro-tips.png)

This guide provides tips and tricks for effectively using Claude Code, a command-line tool for agentic coding.

---

### [日本語 TTS 用の学習データの精度を上げる「ふりがな Whisper」を作った話](https://zenn.dev/parakeet_tech/articles/2591e71094ea58)

![日本語TTS用の学習データの精度を上げる「ふりがなWhisper」を作った話](https://res.cloudinary.com/zenn/image/upload/s--Vi7BZ2ft--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E6%2597%25A5%25E6%259C%25AC%25E8%25AA%259ETTS%25E7%2594%25A8%25E3%2581%25AE%25E5%25AD%25A6%25E7%25BF%2592%25E3%2583%2587%25E3%2583%25BC%25E3%2582%25BF%25E3%2581%25AE%25E7%25B2%25BE%25E5%25BA%25A6%25E3%2582%2592%25E4%25B8%258A%25E3%2581%2592%25E3%2582%258B%25E3%2580%258C%25E3%2581%25B5%25E3%2582%258A%25E3%2581%258C%25E3%2581%25AAWhisper%25E3%2580%258D%25E3%2582%2592%25E4%25BD%259C%25E3%2581%25A3%25E3%2581%259F%25E8%25A9%25B1%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_34:H.%2520Enomoto%2Cx_220%2Cy_108/bo_3px_solid_rgb:d6e3ed%2Cg_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzgzNmJlNDAxZmQuanBlZw==%2Cr_20%2Cw_90%2Cx_92%2Cy_102/co_rgb:6e7b85%2Cg_south_west%2Cl_text:notosansjp-medium.otf_30:Parakeet%2520%25E6%25A0%25AA%25E5%25BC%258F%25E4%25BC%259A%25E7%25A4%25BE%2Cx_220%2Cy_160/bo_4px_solid_white%2Cg_south_west%2Ch_50%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyL2FkMTdkMzc2NWUuanBlZw==%2Cr_max%2Cw_50%2Cx_139%2Cy_84/v1627283836/default/og-base-w1200-v2.png)

---

### [AI エージェント規格「MCP」が 3 ヶ月ぶりにアプデ！ どこが変わったの？ - Qiita](https://qiita.com/minorun365/items/cbf4e475e6dd9892ee11)

![AIエージェント規格「MCP」が3ヶ月ぶりにアプデ！ どこが変わったの？ - Qiita](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-user-contents.imgix.net%2Fhttps%253A%252F%252Fcdn.qiita.com%252Fassets%252Fpublic%252Ftech-festa-ogp-background-4b5015b2c518c7e6b9062a7c9f5f5e90.png%3Fixlib%3Drb-4.0.0%26w%3D1200%26blend64%3DaHR0cHM6Ly9xaWl0YS11c2VyLXByb2ZpbGUtaW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1pbWFnZS1zdG9yZSUyRjAlMkYxNjMzODU2JTJGYzIyNmJjMzRhYzZjNDVhMjFmNWU1MTJkMWM3MmE2ZjA5NzQ5NDU3OCUyRnhfbGFyZ2UucG5nJTNGMTY5OTk1NDk3Nj9peGxpYj1yYi00LjAuMCZhcj0xJTNBMSZmaXQ9Y3JvcCZtYXNrPWVsbGlwc2UmYmc9RkZGRkZGJmZtPXBuZzMyJnM9OTJkN2MxNTZiZmM5ZmNiZDk4MWIxZjFiNDMzNzRlOWU%26blend-x%3D120%26blend-y%3D462%26blend-w%3D90%26blend-h%3D90%26blend-mode%3Dnormal%26mark64%3DaHR0cHM6Ly9xaWl0YS1vcmdhbml6YXRpb24taW1hZ2VzLmltZ2l4Lm5ldC9odHRwcyUzQSUyRiUyRnMzLWFwLW5vcnRoZWFzdC0xLmFtYXpvbmF3cy5jb20lMkZxaWl0YS1vcmdhbml6YXRpb24taW1hZ2UlMkYxZTIwZGI1ZTdlNDA3ZWFlN2I5NzBlYzk5OTg4MGRjOGMzY2MwZjY0JTJGb3JpZ2luYWwuanBnJTNGMTY2NzI3NDk2Mz9peGxpYj1yYi00LjAuMCZ3PTQ0Jmg9NDQmZml0PWNyb3AmbWFzaz1jb3JuZXJzJmNvcm5lci1yYWRpdXM9OCZiZz1GRkZGRkYmYm9yZGVyPTIlMkNGRkZGRkYmZm09cG5nMzImcz0xMzQ4OTg3MjlkMzMwYTdiNWRhMzRkOGU2MzVmZjIxOA%26mark-x%3D186%26mark-y%3D515%26mark-w%3D40%26mark-h%3D40%26s%3Da8c9ec491fd51ae80feca7a202022161?ixlib=rb-4.0.0&w=1200&fm=jpg&mark64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTk2MCZoPTMyNCZ0eHQ9QUklRTMlODIlQTglRTMlODMlQkMlRTMlODIlQjglRTMlODIlQTclRTMlODMlQjMlRTMlODMlODglRTglQTYlOEYlRTYlQTAlQkMlRTMlODAlOENNQ1AlRTMlODAlOEQlRTMlODElOEMzJUUzJTgzJUI2JUU2JTlDJTg4JUUzJTgxJUI2JUUzJTgyJThBJUUzJTgxJUFCJUUzJTgyJUEyJUUzJTgzJTk3JUUzJTgzJTg3JUVGJUJDJTgxJTIwJUUzJTgxJUE5JUUzJTgxJTkzJUUzJTgxJThDJUU1JUE0JTg5JUUzJTgyJThGJUUzJTgxJUEzJUUzJTgxJTlGJUUzJTgxJUFFJUVGJUJDJTlGJnR4dC1hbGlnbj1sZWZ0JTJDdG9wJnR4dC1jb2xvcj0lMjNGRkZGRkYmdHh0LWZvbnQ9SGlyYWdpbm8lMjBTYW5zJTIwVzYmdHh0LXNpemU9NTYmdHh0LXBhZD0wJnM9NTI1N2MxMjI5MjY4YTJhMjlmMGNlOTM5MWJmODg2NGY&mark-x=120&mark-y=112&blend64=aHR0cHM6Ly9xaWl0YS11c2VyLWNvbnRlbnRzLmltZ2l4Lm5ldC9-dGV4dD9peGxpYj1yYi00LjAuMCZ3PTgzOCZoPTU4JnR4dD0lNDBtaW5vcnVuMzY1JnR4dC1jb2xvcj0lMjNGRkZGRkYmdHh0LWZvbnQ9SGlyYWdpbm8lMjBTYW5zJTIwVzYmdHh0LXNpemU9MzYmdHh0LXBhZD0wJnM9YmUwNTZlMDcwNzgwOTA0MDdiMDk0Y2NkZmQ4ZGEyYzM&blend-x=242&blend-y=454&blend-w=838&blend-h=46&blend-fit=crop&blend-crop=left%2Cbottom&blend-mode=normal&txt64=S0RESeOCouOCuOODo-OCpOODq-mWi-eZuuOCu-ODs-OCv-ODvOagquW8j-S8muekvg&txt-x=242&txt-y=539&txt-width=838&txt-clip=end%2Cellipsis&txt-color=%23FFFFFF&txt-font=Hiragino%20Sans%20W6&txt-size=28&s=93faacb38d6f768b04b4b01c45086d4f)

この記事は人力で書きました。 主に AI エージェントとツールの接続を標準化するのに使われている Model Context Protocol。 急速に普及が進んでいますが、その仕様は絶賛策定中です。 前回の改版 2025/3/26 から約 3 ヶ月、先週 6/18 に大きなアップデ...

---

### [X ユーザーの Oikon＠外資 IT エンジニアさん: 「Claude Code 初学者 勉強会をアーカイブで見て学びも多かった。 特に@ryoppippi さんの PR レビューの仕組みが先進的で、 ・CodeRabbit ・Copilot ・Gemini にレビューさせて、Claude Code の/pr-comments で収集するの頭良すぎて感動した。個人開発や OSS やっている人は真似した方が良い。」 / X](https://x.com/gaishi_narou/status/1937161494942429584)

![XユーザーのOikon＠外資ITエンジニアさん: 「Claude Code初学者 勉強会をアーカイブで見て学びも多かった。  特に@ryoppippi さんのPRレビューの仕組みが先進的で、  ・CodeRabbit ・Copilot ・Gemini  にレビューさせて、Claude Codeの/pr-commentsで収集するの頭良すぎて感動した。個人開発やOSSやっている人は真似した方が良い。」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [Claude Code 時代のソフトウェアエンジニア生存戦略｜ suthio](https://note.com/suthio/n/n4f79fbe4efda?sub_rt=share_b)

![Claude Code時代のソフトウェアエンジニア生存戦略｜suthio](https://assets.st-note.com/production/uploads/images/197611055/rectangle_large_type_2_a981561b24ea51b02c900bf5941cf776.png?fit=bounds&quality=85&width=1280)

Claude Code が変えた開発の風景 Claude Code を使い始めて約 1 ヶ月経ちますが「Claude Code を使ってから、開発の概念が根本的に変わった」と僕は思ってる。 Cline や Cursor Agent の登場でもでも相当変わったと思う。でも Claude Code はそれ以上の変化だと僕は感じている。何が根本的に違うのか。 自走力の高い Claude Code - ファイルを読み、修正し、テストを実行し、エラーを解決する。まるでペアプロしているような体験。 コードを書く能力が高い Claude 4 Opus - 複雑なロジックも正確に実装できる圧倒的なコード

---

### [TypeGPU 入門](https://zenn.dev/emadurandal/books/e5a5db5066ec17)

![TypeGPU入門](https://static.zenn.studio/images/logo-only-dark.png)

GPU をシンプルに扱えるライブラリ TypeGPU を使ってみよう

---

### [「おしゃべり AI エージェント」誕生物語。開発者が語る、話したくなる AI のつくり方](https://blog.ailia.ai/pickup/ailia-ai-agent-02/)

![「おしゃべりAIエージェント」誕生物語。開発者が語る、話したくなるAIのつくり方](https://blog.ailia.ai/wp-content/uploads/2025/06/7ED750FD-C3B7-4715-94E1-A3DB3738976F.jpg)

開発者の遊び心から生まれた、親しめる AI エージェント ——まずは、伊藤さんが代表を務める「おなかソフト」について教えてください。 伊藤 周氏（以下：伊藤氏）：私が代表を務めるおなかソフトは、Unity コンサルタンティング […]

---

### [Claude Code の指示忘れ問題を解決！Hooks で Python 環境を pip 禁止＆uv 統一にする](https://zenn.dev/gotalab/articles/2fe8d7a15409c8)

![Claude Codeの指示忘れ問題を解決！HooksでPython環境をpip禁止＆uv統一にする](https://res.cloudinary.com/zenn/image/upload/s---etTYa0a--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AE%25E6%258C%2587%25E7%25A4%25BA%25E5%25BF%2598%25E3%2582%258C%25E5%2595%258F%25E9%25A1%258C%25E3%2582%2592%25E8%25A7%25A3%25E6%25B1%25BA%25EF%25BC%2581Hooks%25E3%2581%25A7Python%25E7%2592%25B0%25E5%25A2%2583%25E3%2582%2592pip%25E7%25A6%2581%25E6%25AD%25A2%25EF%25BC%2586uv%25E7%25B5%25B1%25E4%25B8%2580%25E3%2581%25AB%25E3%2581%2599%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:Gota%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzE3OGM0MmRlZjIuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code ではじめる Agentic Coding 入門 - Sansan Tech Blog](https://buildersbox.corp-sansan.com/entry/2025/07/03/142500)

![Claude CodeではじめるAgentic Coding入門 - Sansan Tech Blog](https://ogimage.blog.st-hatena.com/10257846132608666252/6802418398475417624/1751521241)

Bill One Engineering Unit の Purchasing Group でアーキテクトを務める豊田(@helloyuki\_)です。今日は業務中に行っている Agentic Coding について紹介したいと思います。 Agentic Coding とは 定義 Vibe Coding との違い Claude Code とは 定義と機能 特徴 IDE（IntelliJ）との統合 実務での利用事例 何をやらせてみたか どうやったか 学んだこと 探索空間を絞る Plan Mode は積極的に利用する doc の整備を進める MCP サーバーの活用 作業が軌道にのるまで「手懐け」 Bill One での AI 駆…

---

### [Cline を 200 人で試してみた - モノタロウの AI 駆動開発実践記 - MonotaRO Tech Blog](https://tech-blog.monotaro.com/entry/2025/07/02/090000)

![Clineを200人で試してみた - モノタロウのAI駆動開発実践記 - MonotaRO Tech Blog](https://cdn.image.st-hatena.com/image/scale/b3f449f7a007d699b1d2b5516f494bef07c90030/backend=imagemagick;version=1;width=1300/https%3A%2F%2Fcdn-ak.f.st-hatena.com%2Fimages%2Ffotolife%2Fm%2Fmonotaro-tech-blog%2F20250701%2F20250701191857.png)

こんにちは。株式会社 MonotaRO CTO-Office AI 駆動開発チームリーダーの市原です。 先日、2025 年 6 月 24 日に開催された Findy 様のイベントにて、「モノタロウの AI 駆動開発 Cline 編」というテーマで発表させていただきました。今回は、その内容をベースに、私たちが Cline を 200 人規模で導入し、運用してきた実体験をお伝えしたいと思います。 findy.connpass.com speakerdeck.com なぜモノタロウは Cline に着目したのか モノタロウでは、AI の登場をインターネット登場に比肩する変革と捉えており、「大きく導入、後から検証」という方針で全社的に AI…

---

### [Claude Code の「すぐルール忘れる問題」を解決する超効果的な方法を見つけた気がする](https://zenn.dev/sesere/articles/0420ecec9526dc)

![Claude Codeの「すぐルール忘れる問題」を解決する超効果的な方法を見つけた気がする](https://res.cloudinary.com/zenn/image/upload/s--4ISgUHFQ--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AE%25E3%2580%258C%25E3%2581%2599%25E3%2581%2590%25E3%2583%25AB%25E3%2583%25BC%25E3%2583%25AB%25E5%25BF%2598%25E3%2582%258C%25E3%2582%258B%25E5%2595%258F%25E9%25A1%258C%25E3%2580%258D%25E3%2582%2592%25E8%25A7%25A3%25E6%25B1%25BA%25E3%2581%2599%25E3%2582%258B%25E8%25B6%2585%25E5%258A%25B9%25E6%259E%259C%25E7%259A%2584%25E3%2581%25AA%25E6%2596%25B9%25E6%25B3%2595%25E3%2582%2592%25E8%25A6%258B%25E3%2581%25A4%25E3%2581%2591%25E3%2581%259F%25E6%25B0%2597%25E3%2581%258C%25E3%2581%2599%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:sesere%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzg4NjY3ZDcwMjMuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code を「最強の相棒」に！Hooks 機能 完全ガイド（/hooks 画面も徹底解説）🚀 ｜ Kyutaro](https://note.com/kyutaro15/n/n20a1862a46e2?sub_rt=share_b)

![Claude Codeを「最強の相棒」に！Hooks機能 完全ガイド（/hooks画面も徹底解説）🚀｜Kyutaro](https://assets.st-note.com/production/uploads/images/199424958/rectangle_large_type_2_919882d69b1f878fdd7b7d57e045c286.png?fit=bounds&quality=85&width=1280)

AI コーディングアシスタント「Claude Code」を、もっと自分好みに、もっと賢く、もっと頼れる存在にしたい…！そう考えたことはありませんか？ 「毎回同じフォーマットを指示するのが、地味に面倒…」 「このコマンドは使ってほしくないのに、AI が提案してきちゃう…」 「チームで決めたコーディング規約を、AI にも守ってほしい！」 開発の現場では、こうした「ちょっとした手間」や「AI との意思疎通のズレ」が積み重なって、ストレスになることもありますよね。 もし、こうしたルールを一度設定するだけで、Claude が常に守ってくれるとしたら…？ それを実現するのが、今回ご紹介する「Ho

---

### [Common workflows - Anthropic](https://docs.anthropic.com/en/docs/claude-code/common-workflows#run-parallel-claude-code-sessions-with-git-worktrees)

![Common workflows - Anthropic](https://anthropic.mintlify.app/_next/image?url=%2Fapi%2Fog%3Fdivision%3DDocumentation%26mode%3Dlight%26title%3DCommon%2Bworkflows%26description%3DLearn%2Babout%2Bcommon%2Bworkflows%2Bwith%2BClaude%2BCode.%26logoLight%3Dhttps%253A%252F%252Fmintlify.s3.us-west-1.amazonaws.com%252Fanthropic%252Flogo%252Flight.svg%26logoDark%3Dhttps%253A%252F%252Fmintlify.s3.us-west-1.amazonaws.com%252Fanthropic%252Flogo%252Fdark.svg%26primaryColor%3D%25230E0E0E%26lightColor%3D%2523D4A27F%26darkColor%3D%25230E0E0E&w=1200&q=100)

Learn about common workflows with Claude Code.

---

### [Claude Code の Hooks で作業が終わった後にフォーマッターを実行する](https://azukiazusa.dev/blog/claude-code-hooks-run-formatter/)

![Claude Code の Hooks で作業が終わった後にフォーマッターを実行する](https://azukiazusa.dev/blog/ogp/claude-code-hooks-run-formatter.png)

Claude Code hooks は Claude Code のライフサイクルの特定のタイミングで実行されるユーザー定義のシェルスクリプトです。hooks を使用することで、コードのフォーマットを常に実行することができます。この記事では hooks を使用してコードの変更後に prettier が実行されるように設定してみましょう。

---

### [Claude Code Deep Dive 〜t-wada, mizchi と Agentic Coding の「今」を眺める 〜](https://www.youtube.com/live/HqXg2vfGX3c)

![Claude Code Deep Dive 〜t-wada, mizchiとAgentic Codingの「今」を眺める 〜](https://i.ytimg.com/vi/HqXg2vfGX3c/maxresdefault.jpg)

X : #claude_code_deep_diveconnpass : https://cartaholdings.connpass.com/ev...【パネルディスカッションテーマ】・実用で見え始めた「技術的負債」やハイプ・カーブの"幻滅期"におけるリアルな課題・AIで「脳のリミッターが外れる」感覚とは何か？...

---

### [X ユーザーのまさお@AI 駆動開発さん: 「🚨 Cursor が Web アプリ機能を公開しました！ 結論: とても良い これにより ✅ どこからでも、スマホでもタブレットも開発 ✅ o3, sonnet, opus の MAX を組み合わせ可 ✅ 並列可/PR や merge も簡単に 気になる課金は、 従量課金 Mode をオン必須ですが、 追加課金の形跡はありませんでした(スレッド参照) https://t.co/G2HR6mqMPV」 / X](https://x.com/AI_masaou/status/1939814038860611639)

![Xユーザーのまさお@AI駆動開発さん: 「🚨 CursorがWebアプリ機能を公開しました！  結論: とても良い  これにより ✅ どこからでも、スマホでもタブレットも開発 ✅ o3, sonnet, opusのMAXを組み合わせ可  ✅ 並列可/PRやmergeも簡単に  気になる課金は、 従量課金Modeをオン必須ですが、 追加課金の形跡はありませんでした(スレッド参照) https://t.co/G2HR6mqMPV」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [X ユーザーのぬこぬこさん: 「初めての AI Gateway！ログ取得できるの便利 1. Cloudflare を開いて Cmd + K で AI Gateway を検索 2. ゲートウェイの作成から名前を指定 3. 右上 API から API エンドポイントをコピー 4. 環境変数を指定 export ANTHROPIC_BASE_URL=https://t.co/IgFsmV1rSZ&lt;ACCOUND_ID&gt;/claude-code/anthropic https://t.co/rpBruQCzPn」 / X](https://x.com/schroneko/status/1939589128259277222)

![Xユーザーのぬこぬこさん: 「初めての AI Gateway！ログ取得できるの便利  1. Cloudflare を開いて Cmd + K で AI Gateway を検索 2. ゲートウェイの作成から名前を指定 3. 右上 API から API エンドポイントをコピー 4. 環境変数を指定  export ANTHROPIC_BASE_URL=https://t.co/IgFsmV1rSZ<ACCOUND_ID>/claude-code/anthropic https://t.co/rpBruQCzPn」 / X](https://abs.twimg.com/responsive-web/client-web/icon-ios.77d25eba.png)

---

### [iPhone"だけ"で Claude Code を実行する](https://zenn.dev/fbbp/articles/2713be9b82db88)

![iPhone"だけ"でClaude Codeを実行する](https://res.cloudinary.com/zenn/image/upload/s--MU37TTnl--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:iPhone%2522%25E3%2581%25A0%25E3%2581%2591%2522%25E3%2581%25A7Claude%2520Code%25E3%2582%2592%25E5%25AE%259F%25E8%25A1%258C%25E3%2581%2599%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:fbbp%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUNnOG9jSWdDZkJfU2dPc1FxMkZwYnZmWWM5N3QyQ3R0UzBVMC1lWXNLOTR1Zk5ZZXc9czk2LWM=%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [速習 Claude Code](https://zenn.dev/mizchi/articles/claude-code-cheatsheet)

![速習 Claude Code](https://res.cloudinary.com/zenn/image/upload/s--6G1zjVdT--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_72:%25E9%2580%259F%25E7%25BF%2592%2520Claude%2520Code%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:mizchi%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EtL0FPaDE0R2liclRHT052Z3d3ay1fNGxlcVk4TGNGSlNuX0FoWnpEWVlKaXJNcWc9czI1MC1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [日常的に Claude Code を使うようになって便利だと思った Tips 集](https://zenn.dev/yareyare/articles/99f176a8b1c3a9)

![日常的にClaude Codeを使うようになって便利だと思ったTips集](https://res.cloudinary.com/zenn/image/upload/s--iM3n_9WL--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:%25E6%2597%25A5%25E5%25B8%25B8%25E7%259A%2584%25E3%2581%25ABClaude%2520Code%25E3%2582%2592%25E4%25BD%25BF%25E3%2581%2586%25E3%2582%2588%25E3%2581%2586%25E3%2581%25AB%25E3%2581%25AA%25E3%2581%25A3%25E3%2581%25A6%25E4%25BE%25BF%25E5%2588%25A9%25E3%2581%25A0%25E3%2581%25A8%25E6%2580%259D%25E3%2581%25A3%25E3%2581%259FTips%25E9%259B%2586%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:%25E7%2594%25B0%25E4%25B8%25AD%25E5%25A4%25AA%25E9%2583%258E%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUNnOG9jSjZWcVBoWEgwaXVsS05VYlRVOElzXzVQbGVvWV9DVk5VZVZnbjhDRWkwPXM5Ni1j%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [初学者でも今すぐできる、Claude Code の生産性を 10 倍上げる Tips](https://speakerdeck.com/s4yuba/chu-xue-zhe-demojin-sugudekiru-claude-codenosheng-chan-xing-wo10bei-shang-gerutips)

![初学者でも今すぐできる、Claude Codeの生産性を10倍上げるTips](https://files.speakerdeck.com/presentations/88725bf4938d46b9bd51a2f7f6184419/slide_0.jpg?35720594)

2025 年 7 月 5 日に開催された「Claude Code 初学者 勉強会 2」の登壇資料です。

https://currypurin-dojo.connpass.com/event/360112/

---

### [Claude 向け人名＋テクニック一覧(t_wada さんの TDD など) - くらげになりたい。](https://www.memory-lovers.blog/entry/2025/06/27/102550)

![Claude向け人名＋テクニック一覧(t_wadaさんのTDDなど) - くらげになりたい。](https://ogimage.blog.st-hatena.com/12921228815718008255/6802418398489574531/1750987550)

このあたりのツイートを見て、よいなとおもったので、 Claude さんにリストアップしてもらった(_´ω ｀_) 「t_wada さんの TDD」など、人名を追加すると精度がよいっぽい Claude Code に TDD を実行させたいとき、「t-wada の推奨する進め方に従ってください」がめっちゃ効く— hori (@hori_ryota) June 23, 2025 TDD だけでなく「リファクタリング」も意味の希薄化が激しいので、AI に「リファクタリングして」と指示しても効き目がいまいちなことが多々ある。これも人名を出して文脈を境界付けるのが面白そう。「Fowler の」とか「Kent Beck の Ti…

---

### [Gemini CLI のコードを読んで内部処理を理解する](https://zenn.dev/danimal141/articles/ea29bb42d75d43)

![Gemini CLIのコードを読んで内部処理を理解する](https://res.cloudinary.com/zenn/image/upload/s--uu7Hn3uK--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Gemini%2520CLI%25E3%2581%25AE%25E3%2582%25B3%25E3%2583%25BC%25E3%2583%2589%25E3%2582%2592%25E8%25AA%25AD%25E3%2582%2593%25E3%2581%25A7%25E5%2586%2585%25E9%2583%25A8%25E5%2587%25A6%25E7%2590%2586%25E3%2582%2592%25E7%2590%2586%25E8%25A7%25A3%25E3%2581%2599%25E3%2582%258B%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:danimal141%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzVlMzc0YjE0N2UuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Agent2Agent 入門 (12) - ADK Agent ｜ npaka](https://note.com/npaka/n/n0793d8d4430d?sub_rt=share_b)

![Agent2Agent 入門 (12) - ADK Agent｜npaka](https://assets.st-note.com/production/uploads/images/200475195/rectangle_large_type_2_dc8ebaecb3d59589960848f865e1e13d.png?fit=bounds&quality=85&width=1280)

「Agent2Agent」の公式サンプル「ADK Agent」を試したのでまとめました。 前回

1.  ADK Agent Google Agent Development Kit (ADK) を使用して、A2A を使用して通信するシンプルなファクトジェネレータを作成します。 2. セットアップ セットアップ手順は、次のとおりです。 (1) プロジェクトフォルダの作成 mkdir adk_facts
    cd adk_facts (2) Python の仮想環境の準備。 Python 3.11 以上を使用します。 ・Mac python -m venv .venv

---

### [Agentic coding 革命が "成った" 世界で…… - Islands in the byte stream](https://gfx.hatenablog.com/entry/2025/07/06/182751)

![Agentic coding革命が "成った" 世界で…… - Islands in the byte stream](https://ogimage.blog.st-hatena.com/13208692334729887881/6802418398475810311/1751801592)

今年に入ってすぐくらいから、coding agent を活用した、いわゆる vibe coding を行うようになりました。 vibe coding とは、おおむね「自然言語で coding agent に指示をしてプロダクトを作る」という開発スタイルのことを指すとみていいようです\*1。 これはまさにソフトウェア開発における革命です。しかも、この革命はすでに "成って" います。 たとえば、ここ 1 ヶ月くらいで私が仕事で生産するコードの 8 割くらいは、coding agent によるものです。そして、おそらく 1 年以内にこれは 9 割を超えます。 この流れはもはや不可逆です。すでに vibe coding によって作…

---

### [Claude Code × HCP Terraform でセキュアなインフラ自動構築を実現する | DevelopersIO](https://dev.classmethod.jp/articles/claude-code-hcp-tf-authentication-information-management/)

![Claude Code × HCP Terraformでセキュアなインフラ自動構築を実現する | DevelopersIO](https://images.ctfassets.net/ct0aopd36mqt/wp-thumbnail-75c24212db08a605cf51b1578f9a040c/f14b12b1b1cf9b5ed2427490ff86734d/eyecatch_anthropic)

---

### [Cognition | Don’t Build Multi-Agents](https://cognition.ai/blog/dont-build-multi-agents)

![Cognition | Don’t Build Multi-Agents](https://cdn.sanity.io/images/2mc9cv2v/production/5cc0225a1866e9188ee43e39c16676c94a21fd82-1725x1068.png)

Frameworks for LLM Agents have been surprisingly disappointing. I want to offer some principles for building agents based on our own trial & error, and explain why some tempting ideas are actually quite bad in practice.

---

### [Claude Code に要件をヒアリングしてもらった体験がかなり良かった](https://speakerdeck.com/ryuki0947/the-experience-of-having-claude-code-gather-requirements-was-quite-good)

![Claude Codeに要件をヒアリングしてもらった体験がかなり良かった](https://files.speakerdeck.com/presentations/f34c5fabbc68440882536ea29aa569d3/slide_0.jpg?35720857)

---

### [Claude Code の Context Engineering](https://speakerdeck.com/schroneko/context-engineering)

![Claude Code の Context Engineering](https://files.speakerdeck.com/presentations/46ea70811e5b4ad6932edf31b7f4424d/slide_0.jpg?35720835)

---

### [kinopeee/cursorrules](https://github.com/kinopeee/cursorrules)

![kinopeee/cursorrules](https://opengraph.githubassets.com/aa807536fd4c53c49eaadf475a3b8b3b3a308cc24ee293299333de0b75bbf546/kinopeee/cursorrules)

Contribute to kinopeee/cursorrules development by creating an account on GitHub.

---

### [Claude Code によるコミットメッセージ生成](https://zenn.dev/7shi/articles/20250704-auto-commit)

![Claude Codeによるコミットメッセージ生成](https://res.cloudinary.com/zenn/image/upload/s--TYWFrl_M--/c_fit%2Cg_north_west%2Cl_text:notosansjp-medium.otf_55:Claude%2520Code%25E3%2581%25AB%25E3%2582%2588%25E3%2582%258B%25E3%2582%25B3%25E3%2583%259F%25E3%2583%2583%25E3%2583%2588%25E3%2583%25A1%25E3%2583%2583%25E3%2582%25BB%25E3%2583%25BC%25E3%2582%25B8%25E7%2594%259F%25E6%2588%2590%2Cw_1010%2Cx_90%2Cy_100/g_south_west%2Cl_text:notosansjp-medium.otf_37:7shi%2Cx_203%2Cy_121/g_south_west%2Ch_90%2Cl_fetch:aHR0cHM6Ly9zdG9yYWdlLmdvb2dsZWFwaXMuY29tL3plbm4tdXNlci11cGxvYWQvYXZhdGFyLzg0Nzg0Y2QxOWQuanBlZw==%2Cr_max%2Cw_90%2Cx_87%2Cy_95/v1627283836/default/og-base-w1200-v2.png)

---

### [Claude Code の --dangerously-skip-permissions を安全に使う Hooks 設定](https://wasabeef.jp/blog/claude-code-secure-bash)

![Claude Code の --dangerously-skip-permissions を安全に使う Hooks 設定](https://wasabeef.jp/images/posts/cc.webp)

Claude Code の PreToolUse フックと deny-check.sh で、権限スキップ時でも危険なコマンドをブロックする方法

---
