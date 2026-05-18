# Microsoft Store Listing — revAIser

## English (en-US)

### App name
revAIser

### Short description (200 char max)
AI-powered text proofreader. Use your own API key from Groq (free), OpenAI, or Anthropic Claude — review and accept each AI suggestion one at a time in a side-by-side diff view.

### Description (long, max ~10000 char)
"The AI rewrote my text, but I have no idea what it actually changed..."
"I don't want to accept everything at once — I want to look at each suggestion myself."

revAIser is built for exactly that.

It's a Windows desktop text proofreader that puts AI suggestions next to your original text in a side-by-side diff view. You step through every change the AI proposes, accept the ones you agree with, and skip the rest. No black box, no all-or-nothing.

**What it's good for**
- Last-mile proofreading on an email draft before you hit Send
- Polishing blog posts, notes, or documentation
- Non-native English or Japanese writing
- Reviewing text drafted by another AI tool, one sentence at a time

**How to use it**
1. Paste text into the left pane, or drag a text file in
2. The first time, set your API key in Settings (Groq is free; sign-up takes a minute)
3. Press Ctrl+Enter — the AI's suggestions appear in the right pane
4. Use Alt+↓ to step to the next change, Alt+← to accept the current one, Ctrl+S to save

**Choose your AI provider**
- **Groq** — free, very fast (Llama 3.3 70B). Sign up at https://console.groq.com — no credit card required
- **OpenAI** — paid, wide model selection (GPT-4o, GPT-4.1, etc.). https://platform.openai.com
- **Anthropic Claude** — paid, strong with nuanced writing (Claude Sonnet / Haiku). https://console.anthropic.com

You set the API key once in Settings, and revAIser sends your text only to the provider you chose. There is no revAIser developer server in the loop. Your key is encrypted on your machine using the Windows credential store. revAIser has no subscription, no ads, and no upsell — your only cost is the AI provider's own usage fee (zero if you pick Groq).

**Other features**
- Character-level highlighting so you see exactly which word or letter changed
- Detail pane that shows the current change in context
- "Accept all" button (Ctrl+Shift+A) for when you trust the AI on a whole document
- English and 日本語 UI, switchable from Settings — including the installer and tray menu
- Dark mode follows your Windows theme automatically
- Ctrl+Shift+Y, from anywhere in Windows, runs revAIser on your clipboard contents

**Keyboard shortcuts**
- Ctrl+O — Open file
- Ctrl+S — Save
- Ctrl+Enter — Run AI check
- Alt+↑ / Alt+↓ — Previous / next change
- Alt+← — Apply current change
- Ctrl+Shift+A — Apply all changes
- Ctrl+Z — Undo
- Ctrl+Shift+Y — Global: launch revAIser with clipboard contents
- Ctrl + scroll wheel — Font size

**Privacy**
The text you submit is sent only to the AI provider you configured (Groq, OpenAI, or Anthropic), and is governed by that provider's privacy policy. Nothing reaches the developer of revAIser — no telemetry, no analytics, no account on our side. Full privacy policy: https://github.com/misstouch-taro/revAIser/blob/main/PRIVACY.md

### What's new in this version
1.0.1 — Microsoft Store tile icon fix. No functional changes from 1.0.0.

### Features (~10 short bullet points)
- AI proofreading via Groq (free), OpenAI, or Anthropic Claude
- Side-by-side diff so you see every change the AI proposes
- Accept or reject each suggestion individually — no all-or-nothing
- Character-level highlighting shows exactly what changed
- Use your own API key; no subscription, no developer-side data collection
- API key encrypted locally via the Windows credential store
- English and 日本語 UI, switchable in-app
- Dark mode follows your Windows theme
- Ctrl+Shift+Y to launch from anywhere with the clipboard contents
- Free; the only cost is the AI provider's usage (Groq is free)

### Search terms / keywords (max 7, each ≤30 chars)
proofreading, diff, AI editor, Groq, OpenAI, Claude, text correction

### Copyright and trademark info (optional)
© 2026 misstouch-taro

### Additional license terms (optional)
MIT License. See https://github.com/misstouch-taro/revAIser/blob/main/LICENSE

### Developed by / Published by (display name)
misstouch-taro

---

## 日本語 (ja-JP)

### アプリ名
revAIser

### 簡単な説明 (200文字以内)
AI でテキスト校正。Groq(無料)/ OpenAI / Anthropic Claude の API キーを設定して、AI の提案を1つずつ確認しながら反映できる差分エディタ。

### 説明 (詳細)
「AI に直してもらったけど、どこを直されたか分からない…」
「全部一括反映は怖いから、提案を1つずつ確認したい」

revAIser はそんなあなたのためのテキスト校正ツールです。

AI(Groq / OpenAI / Anthropic Claude)が提案した校正内容を、元のテキストと左右に並べた差分ビューで表示します。AI が「ここを変えたほうがいい」と提案した箇所を1つずつ巡回しながら、納得できる変更だけを反映できます。AI に丸投げではなく、最終判断はあなたの手の中に。

**こんな場面で使えます**
- 送信前のメール下書きの最終チェック
- ブログ記事・ドキュメントの校正
- 非ネイティブの英語・日本語推敲
- 他の AI で生成した文章を一文ずつ吟味したいとき

**使い方**
1. 左側のペインにテキストを貼り付けるか、ファイルをドラッグ&ドロップ
2. 初回のみ「設定」でプロバイダーの API キーを登録(Groq なら無料、登録は1分)
3. Ctrl+Enter で AI に送信 → 右ペインに提案が並んで表示される
4. Alt+↓ で次の差分へ、Alt+← で気に入った変更だけ反映、Ctrl+S で保存

**3つのプロバイダから選べる**
- **Groq** — 無料・高速(Llama 3.3 70B)。https://console.groq.com でクレカ不要登録
- **OpenAI** — 有料・モデル豊富(GPT-4o, GPT-4.1 等)。https://platform.openai.com
- **Anthropic Claude** — 有料・文章ニュアンスに強い(Claude Sonnet / Haiku)。https://console.anthropic.com

API キーは「設定」画面で一度入力するだけ。revAIser は開発者側のサーバーを持っていないので、あなたのテキストは選んだ AI プロバイダ以外には届きません。キーは Windows の資格情報ストアで暗号化保存されます。revAIser からのサブスクリプション課金や広告は一切なし。コストは選んだプロバイダの利用料だけです(Groq を選べばゼロ円)。

**その他の機能**
- 文字単位の差分ハイライト(単語・文字レベルでどこが変わったか一目瞭然)
- 詳細ペインで現在の差分の前後比較
- 全差分を一括反映ボタン(Ctrl+Shift+A)も用意 — AI を信頼できるときに
- 日本語・英語 UI(インストーラ・トレイメニュー含めて切替可)
- Windows テーマ追従ダークモード
- Ctrl+Shift+Y でどこからでもクリップボード内容を校正

**キーボードショートカット**
- Ctrl+O — ファイルを開く
- Ctrl+S — 保存
- Ctrl+Enter — AI チェック実行
- Alt+↑ / Alt+↓ — 前/次の差分へ
- Alt+← — 現在の差分を反映
- Ctrl+Shift+A — 全差分を反映
- Ctrl+Z — 元に戻す
- Ctrl+Shift+Y — グローバル: クリップボード内容で起動
- Ctrl + マウスホイール — フォントサイズ変更

**プライバシー**
入力したテキストは、設定中の AI プロバイダ(Groq / OpenAI / Anthropic)のサーバーにのみ送信され、各プロバイダの規約に従って処理されます。revAIser 開発者にはデータが届きません(テレメトリ・解析・アカウント登録すべてなし)。詳細はプライバシーポリシー(https://github.com/misstouch-taro/revAIser/blob/main/PRIVACY.md)を参照してください。

### このバージョンの新機能
1.0.1 — Microsoft Store のタイルアイコン表示を修正。機能変更はありません。

### 機能(箇条書き)
- Groq(無料)/ OpenAI / Anthropic Claude による AI 校正
- AI の提案を左右の差分ビューで全件確認
- 1件ずつ承認・拒否できる(全部反映の二択ではない)
- 文字単位のハイライトで「どこが変わったか」が一目瞭然
- API キーは自分のものを設定 — サブスクリプション課金なし、開発者にデータが届かない
- API キーは Windows の資格情報ストアで暗号化保存
- 日本語/英語 UI(設定からいつでも切替)
- Windows テーマ追従ダークモード
- Ctrl+Shift+Y でどこからでもクリップボード内容を校正
- 完全無料(コストは選んだ AI プロバイダの利用料のみ。Groq ならゼロ円)

### 検索キーワード(最大7個、各30文字以内)
校正, 文章校正, AI 校正, 差分, Groq, OpenAI, Claude

### 著作権情報
© 2026 misstouch-taro

### ライセンス条項
MIT License. https://github.com/misstouch-taro/revAIser/blob/main/LICENSE

### 発行者表示名
misstouch-taro
