---
name: ai-market-research
description: >
  Research and report on the latest AI tool and service market trends from X (Twitter), Reddit, and Zenn.
  Covers new launches, major updates, pricing changes, and community discussions across Coding AI, Design AI, AI Agents, LLMs, and more.
  Use this skill for AI market monitoring, AI tool discovery, LLM updates, generative AI trends, or AI SaaS tracking.
  MANDATORY TRIGGERS: AI market research, AI tool trends, LLM updates, coding AI news, design AI news, AI agent updates,
  new AI tool launch, AI pricing change, open source LLM release.
  Also trigger for Japanese queries like: "AIツールの最新動向を調べて", "AI市場の動きをまとめて",
  "コーディングAIの最新情報", "AIエージェント周りで何か動きはある？", "LLMの最新アップデート情報をまとめて".
  Keywords: AI tools, AI market, LLM, generative AI, AI agent, AI SaaS, coding AI, design AI, vibe coding, MCP.
---

# AI Market Research Skill

## Purpose

This skill monitors the latest trends in AI tools and services by searching X (formerly Twitter), Reddit, and Zenn. It produces a structured Markdown report that allows practitioners to catch up on the most impactful developments in minimum time.

The goal is not exhaustive news aggregation. The priority is identifying information that directly affects real-world decisions — tool choices, pricing, workflow changes, and emerging best practices.

## Language Policy

All communication with the user — including clarifying questions, progress updates, summaries, and the final report — must be written in **Japanese**.

All search queries issued to X, Reddit, and Zenn must be written in **English** to maximise coverage of the global AI community.

---

## Glossary of Key Terms

When any of the terms below appear in the report body, include a brief inline parenthetical if context is insufficient for a junior reader.

| Term | Plain-language explanation |
|---|---|
| LLM (Large Language Model) | An AI model trained on massive amounts of text. It can generate, summarise, translate, and reason in natural language. Examples: GPT-4, Claude, Gemini. |
| Generative AI | AI that creates new content — text, images, audio, video, or code — rather than just classifying or predicting. |
| AI Agent | An AI system that can autonomously plan and execute multi-step tasks by calling tools, browsing the web, or writing and running code, without constant human guidance. |
| MCP (Model Context Protocol) | An open standard that lets AI models connect to external tools and data sources (e.g., databases, APIs) in a standardised way. Think of it as a universal adapter plug for AI. |
| API (Application Programming Interface) | A defined interface that lets one software system talk to another. When a pricing change hits an AI API, it affects all developers building products on top of it. |
| Open-source LLM | A language model whose weights (the learned parameters) are publicly released, allowing anyone to run, fine-tune, or redistribute the model. |
| Fine-tuning | Further training a pre-trained model on a smaller, domain-specific dataset to specialise its behaviour. |
| RAG (Retrieval-Augmented Generation) | A technique where an AI retrieves relevant documents from an external knowledge base before generating a response, reducing hallucination. |
| Inference | The process of running a trained AI model to produce an output. "Inference cost" refers to the compute cost of generating responses. |
| Context window | The maximum amount of text (measured in tokens) an LLM can consider at once. Larger context windows allow longer conversations and documents. |
| Vibe coding | An informal term for AI-assisted coding where the developer describes intent in natural language and the AI generates most of the code. |
| AI SaaS | Software-as-a-Service products that embed AI features — e.g., Notion AI, Canva AI, Figma AI. |

---

## Research Target Categories

Only collect information that falls into one of the five categories below. Exclude personal opinions without supporting evidence, speculative predictions, and academic pre-print announcements unless they are accompanied by a release or product launch.

| Category | Definition | Examples |
|---|---|---|
| New Launch | A new AI tool or service goes public or enters beta | New coding AI announced, new LLM provider opens API access |
| Major Update | Significant feature addition, model upgrade, or spec change to an existing tool | Claude gains new capability, Cursor major version release |
| Pricing / Plan Change | Revised pricing, plan restructuring, change to free tier limits | API price reduction, free plan usage cap tightened |
| Shutdown / Acquisition | A tool is discontinued, acquired, or merged into another service | Startup acquired, feature deprecated |
| Practical Trend | A workflow or technique rapidly spreading among practitioners | New prompting pattern goes viral, popular tool combination |

---

## AI Domains to Cover

Research must span all eight domains below. Do not focus exclusively on any single domain.

| Domain | Representative tools / keywords |
|---|---|
| Coding AI (primary focus) | Cursor, GitHub Copilot, Windsurf, Devin, Claude Code, Codeium, Aider, vibe coding |
| Design AI (primary focus) | Figma AI, Canva AI, Midjourney, Adobe Firefly, Galileo AI, Framer AI, v0 (Vercel) |
| AI Agents & Automation (primary focus) | Manus, Claude Cowork, AutoGPT, n8n AI, Zapier AI, MCP servers, browser agents |
| LLM / Chat AI | ChatGPT, Claude, Gemini, Grok, Perplexity, new model releases |
| Image / Video / Audio Generation | DALL-E, Sora, Runway, ElevenLabs, Suno, Kling, HeyGen |
| AI Development Infrastructure | Hugging Face, Replicate, Together AI, Groq, Fireworks AI, Modal |
| Business-Specific AI SaaS | Notion AI, Linear AI, Salesforce Einstein, GitHub Models |
| Open-Source LLM | Llama, Mistral, Qwen, DeepSeek, Phi, Gemma |

---

## Report Period Selection Rules

Determine the date range automatically based on the day of the week when the skill is run.

| Day of execution | Target period | Note |
|---|---|---|
| Tuesday – Friday | Previous 1 day | e.g., Wednesday run covers Tuesday |
| Monday | Previous 3 days (Sat + Sun + Mon) | Catches weekend activity |
| Manual override | User-specified range | e.g., "past 1 week" or "2026-03-01 to 2026-03-07" |

---

## Research Procedure

### Step 1 — Search X (formerly Twitter) in English

Issue all queries in English. Apply a date filter matching the target period for every query.

Accounts to monitor as starting points: Official accounts of AI tools (@OpenAI, @AnthropicAI, @GoogleAI, @cursor_ai, @github, etc.), influential AI researchers, and AI news aggregators with large follower counts.

**English search queries to run:**

Coding AI (primary):

- `new AI coding tool launch`
- `AI code editor update`
- `vibe coding workflow`
- `Cursor update announcement`
- `Claude Code update`
- `GitHub Copilot new feature`

Design AI (primary):

- `AI design tool launch`
- `Figma AI update`
- `v0 Vercel new feature`
- `AI UI generator`
- `generative design tool`

AI Agents (primary):

- `AI agent new release`
- `MCP server launch`
- `autonomous AI agent workflow`
- `AI automation tool update`
- `agentic coding`

General AI market:

- `new AI tool launch`
- `LLM new model release`
- `AI pricing change`
- `AI tool major update`
- `open source LLM release`
- `AI SaaS update`

### Step 2 — Search Reddit in English

Search the subreddits and use the keywords below. Apply the target period date filter.

**Target subreddits:** r/artificial, r/MachineLearning, r/LocalLLaMA, r/ChatGPT, r/ClaudeAI, r/singularity, r/AItools, r/cursor, r/StableDiffusion, r/webdev, r/programming, r/Frontend, r/UI_Design

**Search keywords:**

- `new tool launch`
- `just released`
- `major update`
- `pricing change`
- `switched from X to Y`
- `workflow tip`
- `game changer`
- `AI agent`
- `MCP`
- `vibe coding`
- `AI design tool`

**Prioritisation signals on Reddit:** Posts with high upvote counts in a short time window, posts with many comments indicating active discussion, and posts containing screenshots or concrete use-case descriptions.

### Step 3 — Search Zenn in English

Zenn is a Japanese technical publishing platform, but searching in English still surfaces articles tagged with English keywords. Focus on trend articles and scraps that discuss AI tools.

**Search approach:**

- Search Zenn's topic/tag pages for: `AI`, `LLM`, `cursor`, `claude`, `copilot`, `agent`, `mcp`
- Prioritise articles published within the target period with high "like" counts
- Look for "tried and tested" style articles (実際に使ってみた), workflow introductions, and comparison articles — these reflect real practitioner adoption

### Step 4 — Extract and Classify Information

For each item found across all three sources, record:

- **Tool / Service name:** Use the official name
- **Category:** One of the five categories defined above
- **AI Domain:** One of the eight domains above
- **Summary:** 2–3 sentences explaining what happened
- **User sentiment:** Positive / Negative / Mixed — with key reasons
- **Source:** URL and post date
- **Confidence level:** `Official announcement` / `Credible report` / `Unverified user report`

Exclude posts outside the target date range. Flag any unverified claims explicitly.

### Step 5 — Domain-Level Trend Pickup

After classifying all items, identify the single most-discussed topic per domain.

All eight domains must be addressed. If no relevant posts were found for a domain within the target period, write "No notable topic in this period."

**How to judge "most discussed" (in priority order):**

1. Number of independent mentions across different users and posts on the same topic
2. Total engagement (reposts + likes on X; upvotes + comments on Reddit; likes on Zenn)
3. Depth of discussion (analysis and personal experience outweigh simple link shares)

Up to two topics may be listed for a domain if engagement is nearly equal. Exclude posts that are clearly promotional or sponsored.

### Step 6 — Impact Assessment

Assign one of three impact levels to each item.

| Level | Criteria | Recommended action |
|---|---|---|
| HIGH | Structural market change; directly influences decisions for many users | Review immediately |
| MEDIUM | Affects a specific domain; relevant if you work in that area | Review within the week |
| LOW | Useful background knowledge; no immediate action required | Review when time allows |

When in doubt between two levels, assign the lower one (conservative default).

### Step 7 — Compose the Report

Generate the report using the template below. Write everything in Japanese. Save as a Markdown file with UTF-8 encoding.

---

## Report Template

```markdown
# AI市場調査レポート（YYYY-MM-DD）

> 調査実行日時: YYYY-MM-DD HH:MM JST
> 調査対象期間: YYYY-MM-DD 〜 YYYY-MM-DD（N日分）
> 実行曜日: X曜日
> 調査ソース: X（旧Twitter）/ Reddit / Zenn
> 新規情報数: N件

---

## 用語ミニ解説

> 本レポートで使用する専門用語を冒頭で簡単に説明します。はじめてAI市場レポートを読む方はここを先に確認してください。

- **LLM**: 大規模言語モデル。大量のテキストで学習したAIで、文章の生成・要約・翻訳などができます（例: GPT-4、Claude、Gemini）。
- **AIエージェント**: 人間が細かく指示しなくても、自律的に複数のステップのタスクをこなせるAIシステムです。
- **MCP（Model Context Protocol）**: AIモデルが外部ツールやデータベースに接続するための標準規格。AIのための「共通コンセント」のようなものです。
- **コンテキストウィンドウ**: LLMが一度に処理できるテキストの量（トークン数）。大きいほど長い文書や会話を扱えます。
- **バイブコーディング（Vibe coding）**: AIに自然言語で意図を伝えながらコードを生成させる開発スタイルの俗称です。

---

## HIGH インパクト

### [ツール・サービス名] — [見出し]

- **カテゴリ**: [5カテゴリのいずれか]
- **AI領域**: [8領域のいずれか]
- **概要**: [2〜3文。専門用語には括弧で補足を入れること]
- **ユーザー反応**: [ポジティブ/ネガティブ/賛否両論 + その主な理由]
- **情報の確度**: [公式発表 / 信頼性の高い速報 / ユーザー報告（未確認）]
- **ソース**: [URL]（投稿日: YYYY-MM-DD、ソース: X / Reddit / Zenn）

---

## MEDIUM インパクト

### [ツール・サービス名] — [見出し]

（HIGH と同一フォーマット）

---

## LOW インパクト

### [ツール・サービス名] — [見出し]

（HIGH と同一フォーマット）

---

## AI領域別 注目トピック

> 各領域で対象期間内に最も盛り上がった話題を1件ずつピックアップしています。

| AI領域 | 注目トピック | 盛り上がりの概要 | 言及数 | 代表ソース |
|---|---|---|---|---|
| コーディングAI | [トピック] | [1〜2文] | N件 | [URL] |
| デザインAI | [トピック] | [1〜2文] | N件 | [URL] |
| AIエージェント・自動化 | [トピック] | [1〜2文] | N件 | [URL] |
| LLM / チャットAI | [トピック] | [1〜2文] | N件 | [URL] |
| 画像・動画・音声生成AI | [トピック] | [1〜2文] | N件 | [URL] |
| AI開発基盤 | [トピック] | [1〜2文] | N件 | [URL] |
| 業務特化AI SaaS | [トピック] | [1〜2文] | N件 | [URL] |
| オープンソースLLM | [トピック] | [1〜2文] | N件 | [URL] |

### 領域横断の所見

（複数の領域にまたがるトレンドや、領域間の関連性が見られる場合はここに記載）

---

## トレンドシグナル

> 複数のソースで共通して言及されているテーマや方向性を抽出しています。

- **[トレンドテーマ1]**: [概要と根拠]（言及数: N件）
- **[トレンドテーマ2]**: [概要と根拠]（言及数: N件）
- **[トレンドテーマ3]**: [概要と根拠]（言及数: N件）

---

## 週次サマリー（月曜レポートのみ）

（月曜実行時のみ出力）

### 今週の主要な動き

（3〜5文で要約）

### 来週の注目ポイント

（発表予告、ベータ終了予定、イベント等）

```

---

### Step 8 — リポジトリへのコミット

レポート生成後、以下の手順でAI-Market-Researchリポジトリにコミットする。

#### 8-1. リポジトリの確認

```bash
if [ -d "/workspace/AI-Market-Research" ]; then
  cd /workspace/AI-Market-Research && git pull origin main
else
  git clone git@github-gorilla:gorilla-muscle/AI-Market-Research.git /workspace/AI-Market-Research
  cd /workspace/AI-Market-Research
fi
```

**前提**: ローカルの `~/.ssh/config` に以下の設定が存在すること:

```
Host github-gorilla
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_ed25519_gorilla
```

この設定により、`gorilla-muscle` アカウントのSSH鍵でリポジトリにアクセスする。設定が存在しない場合はユーザーにSSH config設定を案内する。リポジトリが見つからない場合は、ユーザーにリポジトリURLを確認する。

#### 8-2. 年月フォルダの確認と作成

実行日の年月から対象フォルダを決定する。

```bash
YEAR_MONTH=$(date +"%Y-%m")  # 例: 2026-03
TARGET_DIR="/workspace/AI-Market-Research/${YEAR_MONTH}"

if [ ! -d "$TARGET_DIR" ]; then
  mkdir -p "$TARGET_DIR"
fi
```

#### 8-3. レポートファイルの作成

Step 7で構成したレポート内容を、対象フォルダに直接mdファイルとして作成する。

ファイル名: `YYYY-MM-DD.md`（例: `2026-03-25.md`）

同名ファイルが既に存在する場合は `YYYY-MM-DD_N.md`（N = 連番）で保存する。

#### 8-4. コミット

```bash
cd /workspace/AI-Market-Research
git add .
git commit -m "Add AI market report: YYYY-MM-DD"
```

コミットメッセージのフォーマット: `Add AI market report: YYYY-MM-DD`

例: `Add AI market report: 2026-03-25`

#### 8-5. 完了報告

コミット成功後、以下をユーザーに報告する:

- 保存先: `AI-Market-Research/<年月>/<ファイル名>`
- コミットメッセージ
- コミットハッシュ

コミットが失敗した場合は、エラー内容をユーザーに提示する。

**注意**: リモートへのプッシュは自動実行しない。ユーザーが手動で `git push origin main` を実行すること。

---

## Quality Standards

- Always assign a confidence level; clearly distinguish official announcements from user reports
- Mark all unverified or speculative information with "未確認（Unverified）"
- When uncertain between two impact levels, default to the lower one
- If a category has no new information in the target period, write "新規情報なし（No new items）"
- Translate all English source content into Japanese in the report; keep proper nouns and tool names in their original form
- Include brief inline term explanations whenever a technical term first appears in a section, so junior readers do not need to leave the report to understand it

---

## Activation Examples

Use this skill when the user says any of the following:

- `/ai-market-research`
- `/ai-market-research 1週間分`
- `/ai-market-research 2026-03-01 から 2026-03-07`
- 「AIツールの最新動向を調べて」
- 「今週のAI市場の動きをまとめて」
- 「コーディングAIの最新情報を調べて」
- 「デザインAIの動向をまとめて」
- 「AIエージェント周りで何か動きはある？」
- 「新しいAIツールが出てないか調査して」
- 「LLMの最新アップデート情報をまとめて」
