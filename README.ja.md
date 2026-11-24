# Orkas

**オープンソースのAIエージェントが デスクトップに 目標を完成した作業に変え 動き続けるのです**

Orkas はオープンソース (MIT) の 局所初の 多代理デスクトップ アプリ**Commander** 必要なのは: 作業を自分で完成させ,より大きな作業のために ステップを計画し, プログラムや個人エージェントと共に 専門的なエージェントを招集します**Claude Code,Codex,OpenCode,OpenClawおよびHermes-Agent** 協力して取り組む

Orkasは、一度の質問に答えるだけでなく、プロジェクトを継続して進めるためのアプリです。**プロジェクト**に目標、ルール、メモリ、ファイルをまとめるので、新しい会話でも前回の続きから始められます。**ToDo**は人やエージェントに割り当てられます。**Auto-advance**を有効にすると、チームは次のToDoに自動で着手します。**スケジュール実行**では、定型作業を毎時、毎日、毎週、毎月の間隔で繰り返せます。すべてのデータはお使いのコンピューターに保存され、作業が完了すると成果物が手元に届き、内容を確認できます。継続して進める必要がある業務も、安心してOrkasに任せられます。

**[⬇ macOS・Windows版のOrkasをダウンロード](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** — 無料で使えます。組み込みのOrkasモデル用に500クレジットが付くので、APIキーなしで始められます。Claude、OpenAI、Gemini、DeepSeek、Kimi、GLM、Qwen、MiniMax、Doubaoなどのキーや、ローカルのOpenAI互換エンドポイントも使えます。

[![Download for macOS & Windows](https://img.shields.io/badge/Download-macOS%20%26%20Windows-5b57d6?style=for-the-badge)](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Orkas-AI/Orkas?style=flat&logo=github&label=Stars&color=yellow)](https://github.com/Orkas-AI/Orkas/stargazers)
[![Release](https://img.shields.io/github/v/release/Orkas-AI/Orkas?color=blue)](https://github.com/Orkas-AI/Orkas/releases)
[![X: @leochenpm](https://img.shields.io/badge/X-%40leochenpm-black?logo=x)](https://x.com/leochenpm)
[![Website: orkas.ai](https://img.shields.io/badge/Website-orkas.ai-5b57d6)](https://orkas.ai/?source=gh-orkas)

[English](./README.en.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [Español](./README.es.md) · [Bahasa Indonesia](./README.id.md) · [Español (Latinoamérica)](./README.es-419.md) · [Русский](./README.ru.md) · [Português (Brasil)](./README.pt-BR.md) · [Türkçe](./README.tr.md) · [繁體中文](./README.zh-TW.md) · [Tiếng Việt](./README.vi.md) · [Deutsch](./README.de.md) · [ไทย](./README.th.md) · [Français](./README.fr.md) · [Italiano](./README.it.md) · [Português (Portugal)](./README.pt-PT.md) · [العربية](./README.ar.md)

---

https://github.com/user-attachments/assets/4f8b16c8-a192-45a4-b19f-80e8d02c3dab

![Orkas デスクトップ 作業会話と成果物](./resources/app-ui/task-en.png)

---

## チームがもたらすもの

- **ビデオ,声伝達および画像** — 動画スタジオ,声スタジオ,ImageStudio
- **調査報告,SEO監査および市場分析** — DeepResearcher,セオSeoGeoAgent,ストックアナライザー
- **投稿、記事、ニュースレター、スライド資料** — ContentWriter、PptMaker
- **ウェブサイト,UIとコード** — UIDesigner,ProductDeveloper
- **ワード,Excel, PowerPoint,PDFファイル** — OfficeWorker
- **電子商取引** — 商品調査,リストアップ,レビュー分析,販売分析およびカタログ変更,五人の電子商取引代理店から
- **複雑な作業で複数の代理人が必要** — Commanderはそれを分割し,各部体を適切なエージェントに委ね,結果を組み合わせます. 例えば,市場調査がレポート,スライドデッキと打ち上げビデオになる

アプリには、それぞれ独自のスキル、メモリ、ツールを持つ16体の専門エージェントが組み込まれています。[エージェントライブラリ](https://orkas.ai/views/marketplace/gs/agents/?source=gh-orkas)では30体以上から選べます。必要な役割を伝えれば、指揮官に独自のエージェントを作ってもらうこともできます。

<details>
<summary><b>16人のエージェントが集まった</b></summary>

| 面積 | 代理人 | 提供するもの |
| --- | --- | --- |
| 研究と分析 | **DeepResearcher** | 検証された情報源,標識された矛盾と監査可能な報告を備えた証拠に基づく研究 |
| | **SeoGeoAgent** | URL を起点に、テクニカル SEO、コンテンツ品質、Core Web Vitals、AI の回答での引用されやすさ（GEO）を監査し、修正項目を優先順位付きで提示 |
| | **StockAnalyser** | 株式調査,ファクタースクリーン,バックテスト,ポートフォリオリスクチェック,追跡可能なダッシュボード |
| コンテンツ &メディア | **ContentWriter** | 目標,情報源または概要から出版準備が整った記事,ニュースレター,ケーススタディ |
| | **PptMaker** | 編集可能でレビュー可能な PPTX デッキは,テーマ,概要または文書から |
| | **ImageStudio** | ポスター,カバー,ソーシャル画像,インフォグラフィック |
| | **VideoStudio** | 物語,AIプレゼンター,キャプションとダビング,ハイライトクリップ,ローカル化,そして参照ビデオリクリエーション |
| | **VoiceStudio** | 物語,多音声オーディオ,トランスクリプトと字幕,オーディオ編集およびミックス |
| | **UIDesigner** | 編集可能,製品目標,PRD,スクリーンショットまたはFigma素材からHTML初級UI |
| 建物 & オフィス | **ProductDeveloper** | 復習意識のエンジニアリング  PRD を実装し,バグを修正し,リファクター,レビューし,検証可能な結果 |
| | **OfficeWorker** | Word/Excel/PowerPoint/PDFファイルを作成,編集,チェックおよび配信する |
| 電子商取引 | **ECommerceResearcher** | 予算,市場及び調達制限による製品選択 候補者,拒否理由,検証計画 |
| | **ECommerceWriter** | タイトル,詳細ページ,FAQ,画像コピー,ビデオスクリプトはブランドの声で |
| | **ECommerceReviewer** | 評価と評判分析 顧客テーマ,悪いレビューの根本原因,優先事項 |
| | **ECommerceAnalyzer** | 輸出からの売上,利益,広告,返金および物件 調整された指標と決定 |
| | **ECommerceOperator** | カタログ,価格,プロモーション,インベクトリー変更を計画する.接続したツールを通じてのみ実行する |

代理人についてもっと[orkasス.ai/エージェント](https://orkas.ai/agents/?source=gh-orkas)

</details>

### 自分のコンテンツで参考ビデオを再作成する

**VideoStudio** ビデオのリファレンスの動画ファイルと資産を供給:エージェントはフック,情報順序,視覚拍数,行動への呼びかけを分析し,その後,制作前に何を保存し,何を置き換えるべきかを提案します.

これは,ムービーグラフィック説明器,SaaSまたはアプリデモ,および既存の映像から作成された製品広告に最適です.本地的に作成されたテキスト,字幕,物語,クリップは別々に修正できます.AIで生成された映像に焼いたテキストは,その映像を変更する必要があります.

> "30秒間の垂直プロモーションの参考として Reference.mp4 を使って下さい. ハック,タイプ,ペースを保持し,コンテンツを私の製品と画面の録音で置き換えて,まず分解と計画を教えて下さい".

エージェントが読み取れる動画ファイルが必要です。現在、SNSの共有リンクから動画をダウンロードする機能はありません。カメラワークや実写の演技を正確に再現したり、フレーム単位で一致させたりできるとは限りません。詳しくは[参考動画を再現するワークフロー](./resources/builtin/marketplace/agents/79df9cc89f5f/skills/video-craft/references/reference-recreation.md)をご覧ください。

---

## 作業を進め

Orkasは継続的な作業のために作られています

- **プロジェクト** — 目標とルール,メモリ,ファイルなどです. プロジェクトでの会話が始まるので,ゼロから簡単に説明することはありません.
- **作業と自動進捗** — プロジェクトには,人や代理人のタスクリストがあります. Auto-advanceは,次の項目を自分で拾い,完成した作業をあなたのレビューのために持ち帰ります.
- **スケジュール実行** — タスクを毎時、毎日、毎週、毎月の間隔で実行できます。Orkasはお使いのコンピューターで動きます。v1.9以降、スリープ復帰時または起動時に、自動化ごとに過去12時間以内の未実行分のうち直近の1回だけを実行します。
- **コネクタ** — Gmail、Google Calendar、Sheets、Drive、Notion、Slack、Shopify、Stripeなどに接続できます。初期設定では、送信、投稿、削除の前にOrkasが確認します。
- **アプリ** — ツールを記述し,Orkasはデスクトップアプリ内のローカルアプリとして構築します.パッケージ化されたアプリでは,付費プランは公開リンクを持つウェブアプリケーションとしても公開できます.
- **共有プロジェクト** — *(パッケージアプリ)*チームメイトやVAを招待し 各作業を相手や代理人に委ねます

> [!NOTE]
> 共有プロジェクト、クラウド同期、Webアプリの公開はインストール版限定です。オープンソース版では現在利用できません。これらの機能を使うには、**[macOS・Windows版のOrkasをダウンロード](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)**してください（無料、500クレジット付き）。

---

## Claude Code,Codex,OpenCode,OpenClawとHermes-Agentを一緒に実行する

Orkas は既に設置した CLI 代理を局所セッションとして運営しています**Claude Code,Codex,OpenCode** 個人的な代理人**OpenClawとHermes-Agent** Commanderはそれぞれに最も良い部分を委ねて,すべての計画に1つの計画を保持します.それで,単一のチャットでバグを修正し,変更をレビューし,リリースノートを書き込むことができます.

[Claude CodeとCodexを一緒に使って →](https://orkas.ai/blog/claude-code-codex-together/?source=gh-orkas)

---

## なぜOrkas

- **計画,委託,残りをするCommander** — 目標を分解し,適切な代理人,スキル,コネクタやツールを選び,分析,書き込み,研究,ファイル作業を自分で処理する.
- **ローカルファースト** — 会話、ファイル、ナレッジベース、カスタムエージェントは既定で端末に保存されます。インストール版ではクラウド同期を有効にできます。自分のキーを使うとモデルへのリクエストは端末からプロバイダーに直接送られ、組み込みのOrkasモデルはOrkasのマネージドサービスを利用します。
- **モデルならいつでも交換する** — Commanderと内蔵エージェントは,内蔵のOrkasモデル,あなたの独自のプロバイダー,またはローカルエンドポイントを同じモデル設定で設定しています.外部CLIエージェントは独自のモデル設定を維持します.
- **改善するエージェント** — 背景レビューは,アプリが無効で新しい活動を調査し,自己評価,再利用可能な方法,学習されたスキルを磨き出すことができます.
- **オープンソース,ブラックボックスなし** — Orkasや全てのエージェントや技能が何をしているか正確に読む

> ⭐ Orkasが役に立つなら,スターはより多くの人がプロジェクトを見つけるのを助けます.

---

## ダウンロード

| | パッケージ化されたアプリ (推奨) | 源から実行する |
| --- | --- | --- |
| プラットフォーム | macOS 12+ (Apple Silicon & Intel),Windows 10+ | macOS,Windows,glibc 2.34+ Linux x64/arm64 |
| アカウント | ログインすると500クレジットを付与 | 不要 |
| モデル | Orkasのモデル内蔵 または自分の鍵 | 鍵やローカルエンドポイント |
| 含有する | プロジェクトコラボレーション,アプリ公開,クラウドシンクロレーションなど | — |
| 持って来 | **[Orkasダウンロード](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** | [早くスタート](#早くスタート) |

ダウンロードリンクは,あなたのシステムを検出し,適切なインストーラを起動します.

---

## 何のために使ってるんだ

- **マーケティングコンテンツ** — 声でビデオ,製品ページ,投稿,ニュースレターを公開します[コンテンツの書き込み](https://orkas.ai/use/content-writing/?source=gh-orkas) · [ビデオ](https://orkas.ai/use/make-videos/?source=gh-orkas)
- **倉庫業務** — 週刊の販売報告,レビュー回答,リストアップ,競合他社チェック[電子商取引](https://orkas.ai/use/ecommerce/?source=gh-orkas)
- **研究と報告** — 需要に応じてまたは毎週提供される報告やデッキ[研究](https://orkas.ai/use/researchers/?source=gh-orkas) · [データ分析](https://orkas.ai/use/data-analysis/?source=gh-orkas)
- **文書でチャット** — 回答は,自分のファイルに基いて,ソースの文献を引用する.[文書でチャット](https://orkas.ai/use/chat-with-documents/?source=gh-orkas)
- **顧客業務** — 会議報告,月間クライアントレポート,テンプレート更新デッキ[顧客報告の月額模様](https://orkas.ai/blog/monthly-client-report-template/?source=gh-orkas)
- **製品開始** — ランディングページ,テスト,チャングログ,ランニングポストのバグ修正[開発者](https://orkas.ai/use/developers/?source=gh-orkas)
- **アプリを作成する** — 引票計算機,予約フォーム,内部ツール[アプリを作成する](https://orkas.ai/use/build-apps/?source=gh-orkas)
- **小規模なチーム** — 社員が代理人[小規模なチーム](https://orkas.ai/use/small-teams/?source=gh-orkas)

---

## Orkas の 比較

| ツール | 何なのか | Orkas の 違い |
| --- | --- | --- |
| **Claude Code** | ClaudeモデルをベースにしたAnthropicのコーディングエージェント。ターミナル、IDE、デスクトップ、ウェブで使用できます。 | どちらか一方を選ぶ必要はありません。OrkasではClaude Codeをチームの一員として実行できます。さらに、特定のモデルに依存しないエージェントチームが調査、コンテンツ制作、動画制作などの作業も担当し、プロジェクト、タスク、自動化で作業を継続します。[OrkasとClaude Codeの比較 →](https://orkas.ai/compare/orkas-vs-claude-code/?source=gh-orkas) |
| **Codex** | OpenAIのコーディングエージェント。ターミナル、エディター、クラウドで使用できます。 | どちらか一方を選ぶ必要はありません。OrkasではCodexをClaude CodeやOpenCodeと並ぶチームの一員として実行できます。Commanderは実装をCodexに、レビューを別のエージェントに任せ、ドキュメント、リリース告知、動画など、リリースに必要なコード以外の作業も進められます。[OrkasとCodexの比較 →](https://orkas.ai/compare/orkas-vs-codex/?source=gh-orkas) |
| **Claude Cowork** | 日常業務向けのAnthropicのエージェント。Claudeに統合されており、デスクトップ、ウェブ、モバイルで使うにはClaudeの有料プランが必要です。既定ではAnthropicのクラウド上で動作し、Claudeモデルを使います。 | Claude Coworkのオープンソース（MIT）の代替で、500クレジット付きで無料で始められます。エージェントは手元のコンピューターで動作し、データは既定でローカルに保存されます。内蔵Orkasモデル、自分のプロバイダーのAPIキー、ローカルエンドポイントを選べます。CommanderはClaude Code、CodexなどのCLIエージェントも活用できます。一方、Orkasはコンピューターがスリープしていないことが必要ですが、Coworkのクラウドタスクは手元のコンピューターに依存せずに続行できます。[Claude Coworkの代替 →](https://orkas.ai/compare/claude-cowork-alternatives/?source=gh-orkas) |
| **Manus** | 既定でManusのクラウド上でタスクを計画・実行するAIエージェント。デスクトップアプリManus Studio（macOS / Windows）は選択したフォルダーでも作業できますが、タスクの計画は引き続きクラウドで行われます。 | Manusのオープンソース（MIT）の代替です。エージェントは手元のコンピューターで動作し、データは既定でローカルに保存されます。内蔵Orkasモデル、自分のプロバイダーのAPIキー、ローカルエンドポイントを選べ、プロジェクト、タスク、自動化で作業を継続できます。一方、Orkasはコンピューターがスリープしていないことが必要ですが、Manusのクラウドタスクは手元のコンピューターに依存せずに続行できます。[Manusのオープンソース代替 →](https://orkas.ai/open-source-manus-alternative/?source=gh-orkas) |
| **LangChain** | PythonやJavaScriptのアプリにコードで組み込む、開発者向けのLLMアプリ・エージェントフレームワークです。 | Orkasは会話で操作するデスクトップアプリです。データは既定でローカルに保存されます。 |
| **CrewAI** | ロールプレイの自律的なエージェントをオーケストラするための Python フレームワーク コードでクルーとエージェントを定義します | Orkas は デスクトップアプリに 多エージェントのオーケストレーションを 組み込みました プロジェクトやタスク,自動化,各エージェントの 自己改善などです |
| **OpenClaw** | メッセージングサービスとの連携、マルチエージェントルーティング、サブエージェント機能を備えた、個人向けエージェントプラットフォームです。 | Orkasは成果物の作成と納品に適したデスクトップワークスペースです。内蔵の専門エージェントに加え、Claude Code、Codex、OpenCodeなどのCLIエージェントを連携させ、OpenClawもチームの一員として利用できます。 |
| **Hermes-Agent** | ヌス・リサーチの自己改善エージェント 記憶力とスキルを持つエージェントが CLI,メッセージングゲートウェイ,デスクトップアプリとして利用できます | Orkasはチームを調整し,Commanderは多くの専門家や他の CLI 代理人を指揮し,Hermes-Agentがそれらのうちの1つとして介入する. |

**Orkasなら** スタッフではなく スタッフを雇い 数日間動いている作業と 自分のデータ,鍵,エージェントを

**じゃなくて** 単一の汎用チャットボットや 純粋なコードライブラリを 自分のアプリに組み込むだけです

**プログラミング代理人を選ぶか?** [Codex対OpenCode](https://orkas.ai/compare/codex-vs-opencode/?source=gh-orkas) · [Claude Code vs Codex vs OpenCode](https://orkas.ai/compare/claude-code-vs-codex-vs-opencode/?source=gh-orkas) · [Claude Codeの代替品](https://orkas.ai/compare/claude-code-alternatives/?source=gh-orkas)

**完全な横対面比較 →** [クロード・コード vs](https://orkas.ai/compare/orkas-vs-claude-code?source=gh-orkas) · [Codex](https://orkas.ai/compare/orkas-vs-codex?source=gh-orkas) · [クライン vs カーネ](https://orkas.ai/compare/orkas-vs-cline?source=gh-orkas) · [ラングチェイン](https://orkas.ai/compare/orkas-vs-langchain?source=gh-orkas) · [チェットGPT](https://orkas.ai/compare/orkas-vs-chatgpt?source=gh-orkas) · [OpenClawと対照](https://orkas.ai/compare/orkas-vs-openclaw?source=gh-orkas) · [エルメス・エージェント vs.](https://orkas.ai/compare/orkas-vs-hermes-agent?source=gh-orkas)

---

## 早くスタート

代わりにパッケージのインストーラーが欲しいですか?[ダウンロード](#ダウンロード)ソースから実行するには,現在 Linux で Orkas を実行する方法:

**要求**:ノード 22.12+ · macOS / Windows 10+ / glibc 2.34+ Linux x64 または arm64. Python 3 と C/C++ のビルドツールチェーンを珍しいネイティブモジュールソースビルドバックのために利用可能にしておく.

```bash
git clone https://github.com/Orkas-AI/Orkas.git
cd Orkas
./run.sh           # macOS / Linux
run.cmd            # Windows
```

Linuxでソースコードから起動するにはglibc 2.34以降が必要です。Alpineなど、muslをベースとするディストリビューションはサポート対象外です。ソース版の初回起動時に、ローカル音声文字起こし用として、対象アーキテクチャ向けのwhisper.cppランタイムと多言語モデルをダウンロードして検証します。

`run.sh` / `run.cmd`起動時にロックされたnpm依存度木をインストールし,ピースン,UV,ノード,インベディングモデル (~95MB),OfficeCLI,FFmpeg,whisper.cpp,および多言語スピーチモデルリソースを初打ちに準備します.Linuxのスタートアップは,アプリケーションを開く前に,ElectronのABIの下でのプラットフォームネイティブモジュールとWhisper実行時間を検証します.OCRとスキル特有のPythonパッケージは,これらの機能が最初に使用されたときに孤立した地元の環境にインストールされます.初打ちは,作業空間を作成します`~/.orkas/`(macOS / Linux) または`<smallest non-system drive>:\.orkas\`(ウィンドウズ) オープン**設定 → AI プロバイダー** API keyまたはOAuthを追加する

ネイティブ依存関係でエラーが出た場合は、Node.js 24 LTS（最低 22.12.0）を使い、このソースディレクトリで
`npm run native:repair` を実行します。このコマンドはオプションの依存パッケージを復元し、
Electron 用の SQLite ビルドを修復し、SQL と sqlite-vec を検証します。さらに、
同梱の Node ランタイムを準備し、別プロセスで sharp を検証してから成功を報告します。
使用`npm run native:check`設置なしのチェックについて
参照[ネイティブ依存性検証スクリプト](./scripts/verify-native-dependencies.cjs)実施された検査について

---

## 機能する仕組み

### 任務のルーティング

Commanderは一般作業を自分で担当し,専門家の作業を3つのツールで委任する.

- **`dispatch_to`** — 実行するエージェントを指定し,その結果を継続的な作業のために返します. 結果を待つことができます.または無同期で実行して,任務が完了するとCommanderに通知します.
- **`hand_off_to`** は残りの作業を名前で指定したエージェントに引き継ぎ、Commanderの現在のターンを終了します。引き継いだエージェントが直接応答します。必要に応じて後続ステップを設定し、Commanderが後で全体のタスクを再開できるようにします。
- **`run_worker`** — 匿名で孤立したサブタスクを実行し,プライベートの結果を返します. 会話履歴や名前のエージェントのスキルを受信しません.

代理人名と匿名労働者は,別々の同時制御をします.[派遣実施](./src/main/features/group_chat/bus.ts)及び[実行ロック](./src/main/util/locks.ts).

### 文脈管理

実行時間の予算は,選択されたモデルの可用入力容量,提示,ツールおよび持続的な実行時間の状態を考慮するコンテキストです.完了ディオログは,制限された最近の歴史ウィンドウを使用します.長時間アクティブタスクは,以前のプロセスメッセージを凝縮するためにチェックポイントを使用して,最近の作業を維持します.ファイル読み込み,ファイル変更,コマンド実行はまた,コンテキスト圧縮を生き残る構造化されたレコードを持っています.

見て[文脈予算](./src/core-agent/src/agent/context-budget.ts), [セッションの歴史とチェックポイント](./src/core-agent/src/agent/session.ts)及び[作業場記録](./src/core-agent/src/agent/workspace-state.ts).

### 記憶 と 図書館

耐用メモは,ユーザーの好みやプロジェクト情報,各エージェントの再利用可能な知識を別々の範囲に保存します.これらのメモは,図書館の文書インデックスと保存された会話史とは異なります.

ライブラリは文書を段落に分け、ローカルのSQLiteベクトルインデックスを作成します。埋め込みモデルは端末上で動作します。エージェントは `library` で、全体または現在のプロジェクトのライブラリにあるファイルを一覧表示し、関連箇所を検索し、原文を読めます。過去の会話は `chat_history` で別に検索します。

見て[範囲内メモリ](./src/main/features/memory.ts), [文書の抽出](./src/main/util/file_to_chunks.ts), [図書館の道具](./src/main/model/core-agent/kb-tools.ts)及び[会話の復元](./src/main/model/core-agent/chat-history-tools.ts).

### 執行制限と回収

セッションロックと同時実行数の上限で並行作業を制御します。ツールの実行回数の上限、進捗チェックポイント、重複呼び出しの検出、処理段階ごとのアイドル監視により、停滞や繰り返しを抑えます。名前付きエージェントのタスクは個別に追跡・キャンセルできます。受理済みや待機中のタスクは完了として扱いません。

見て[俳優の予算](./src/main/features/group_chat/actor-budgets.ts)年間[代理の実行時間](./src/core-agent/src/agent/runner.ts)及び[デスクトップモデルアダプター](./src/main/model/core-agent/client.ts).

### 活動から学ぶ

バックグラウンドレビューは、アプリのアイドル時にエージェントの新しい活動を確認します。実行間隔と実行範囲には制限があります。自己評価（`COMPETENCE.md`）、再利用できる手法（`LEARNING_STRATEGIES.md`）、習得したスキルを更新することも、保存すべき内容はないと判断することもあります。完了件数ではなく、新しい活動に基づいてレビューを行います。

参照[反映スケジュラー](./src/main/features/reflection-orchestrator.ts)及び[レビュー速報](./src/core-agent/src/evolution/metacognition.ts).

---

## よくある質問

**Orkasって?**
Orkasは、ローカルファーストのオープンソース（MIT）マルチエージェントデスクトップアプリです。指揮官は目標をToDoに分け、16体の組み込み専門エージェントとClaude Code、Codex、OpenCode、OpenClaw、Hermes-Agentを調整し、完成したファイルを届けます。

**API keyが必要か?**
いいえ。インストール版には組み込みのOrkasモデル用に500クレジットが付いています。使い切った後は、クレジットの購入、有料プランの利用、ご自身のプロバイダーキーの追加から選べます。プロバイダーからの請求は別です。

**Orkasはローカルで動く大規模言語モデル（LLM）ですか？**
いいえ。Orkasはお使いのコンピューターで動作し、組み込みのOrkasモデル、ご自身のAPIキーで利用するモデル、またはローカルのモデルエンドポイントのうち、選択したものを呼び出します。Orkas自体はモデルではなく、エージェントとツールを連携させるアプリです。

**Orkasも私の書類から 引用文で答えられるか?**
Orkasは本棚に PDF ファイルや文書を追加し,引用で答えることができます.

**オルマやLMスタジオのような ローカルモデルを使ってもいいですか?**
はい。**アカウント設定 → モデル → チャット → モデルを追加 → カスタム**を開き、**OpenAI互換**または**Anthropic互換**を選択します。ベースURL、正確なモデルID、APIキーを入力し、保存したモデルをタスクのモデル選択欄で選びます。

**API keyとデータはどこに保管されているか?**
データとキーは既定でお使いのコンピューターに保存されます。ご自身のプロバイダーのキーはローカルで暗号化して保存し、クラウドには同期しません。ご自身のキーを使う場合、モデルへのリクエストは端末からプロバイダーに直接送信されます。組み込みのOrkasモデルはOrkasのマネージドサービスを利用します。インストール版でオプションのクラウド同期や共有プロジェクトを使うと、対象データがOrkasのサーバーに保存されます。[セキュリティとデータの取り扱い →](https://orkas.ai/security/?source=gh-orkas)

**Orkasもオフラインで動いているのか?**
ソースビルドは,ローカルモデルエンドポイントに対して完全にオフラインで実行できます.パッケージ化されたアプリはログインする必要があります.クラウドモデルはネットワーク接続が必要です.

**パソコンがオフになった時も 動作し続けますか?**
いいえ。自動進行とスケジュール実行には、コンピューターがスリープしておらず、Orkasが起動している必要があります。v1.9以降は、スリープ復帰時または起動時に各自動化の過去12時間分を確認し、未実行のうち直近の1回だけを実行します。

**アプリを作って公開できますか?**
Orkas内でのローカルアプリは無料です.公開リンクへのウェブアプリを公開するには,付費プランが必要です (Lite 5, Pro 8, Max 15 アプリ),そして公開されたウェブアプリには,Orkas内にあるすべての機能が含まれていません.

**Orkas口座が必要か?**
インストール版は初回起動時にログインが必要です。このリポジトリのソース版にはアカウント機能がなく、そのままアプリが開きます。

**OrkasがClaude Codeと他の情報捜査官を 運転できるのか?**
はい。Claude Code、Codex、OpenCode、OpenClaw、Hermes-Agentの5つの外部CLIエージェントをローカルの子プロセスとして実行できます。HyperFramesなどのオープンソースツールも接続し、同じ会話から調整できます。

**Orkas は Claude Code、Codex、CrewAI、LangChain とどう違いますか？**
Claude CodeとCodexはコーディングエージェントです。Orkasでは両方をチームの一員として使えます。CrewAIとLangChainはコードを中心としたフレームワークです。Orkasは、指揮官が専門エージェントとCLIエージェントを連携させるオープンソースのデスクトップアプリです。複数のモデルプロバイダーから選べ、データとキーは既定でローカルに保存されます。[比較の詳細](https://orkas.ai/compare/?source=gh-orkas)

**Orkasにはどのプラットフォームがサポートされているか?**
macOS 12以降（Apple SiliconとIntel）とWindows 10以降にはインストーラーがあります。glibc 2.34以降を使うLinux x64/arm64にはまだインストーラーがなく、現在はソースコードから実行します。初回起動時に、ローカル音声文字起こし用のwhisper.cppランタイムを指定のバージョンで準備します。Alpineなど、muslをベースとするディストリビューションには対応していません。ソース版の起動にはNode 22.12以降が必要です。Python 3とC/C++ビルドツールチェーンは、ネイティブnpmパッケージに互換性のあるビルド済みバイナリがなく、ローカルで再ビルドする場合にのみ必要です。

**Orkasにはオープンソースが無料ですか?**
はい。OrkasはMITライセンスのもとで無料で使えます。インストール版には内蔵モデル用の500クレジットが付いています。有料プランは月額11.99米ドルからで、毎月のクレジット、クラウド同期、より多くの共有プロジェクト、Webアプリの公開が利用できます。ご自身のキーを使用する場合、モデル利用料はプロバイダーが請求し、Orkasは上乗せしません。[料金 →](https://orkas.ai/pricing/?source=gh-orkas)

---

## ライセンス

[MIT](./LICENSE)
