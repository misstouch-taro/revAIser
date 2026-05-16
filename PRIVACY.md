# Privacy Policy — revAIser

*Last updated: 2026-05-16*

revAIser ("the App") is a desktop application by **misstouch-taro** that helps users proofread and refine their own text using third-party AI providers. This document describes how the App handles your information.

---

## 1. Data the App Does NOT Collect

The App does **not** collect, transmit, or store any personal data on servers operated by the developer. Specifically:

- **No analytics** are gathered.
- **No telemetry** is sent.
- **No user content** is sent to the developer.
- **No identifiers** (device ID, MAC address, email) are recorded by the developer.

---

## 2. Data Stored Locally on Your Device

The App stores the following data on your local computer under `%APPDATA%\revAIser\`:

- **AI provider API keys** — encrypted via Electron `safeStorage` (which uses the operating system's user-scope keystore: DPAPI on Windows).
- **Application preferences** — selected AI model, language (ja/en), dark-mode preference, custom system prompts.
- **Window state** — last window position/size (if applicable).

None of this data leaves your machine through the App itself. Uninstalling the App or running the bundled reset script removes this data.

---

## 3. Text Sent to Third-Party AI Providers

When you press "Check" (Ctrl+Enter) the App transmits the text in the left pane, together with the API key **you** entered for the selected provider, to one of the following services:

| Provider | Service | Provider Privacy Policy |
|----------|---------|--------------------------|
| Groq | https://groq.com | https://groq.com/privacy-policy/ |
| OpenAI | https://openai.com | https://openai.com/policies/privacy-policy |
| Anthropic | https://www.anthropic.com | https://www.anthropic.com/legal/privacy |

Your usage of these services is governed by the respective provider's terms and privacy policy. The developer of revAIser has no visibility into, or control over, the data once it leaves your computer.

**Recommendation**: do not paste confidential or regulated information (PII, trade secrets, medical records, source code under NDA, etc.) into the App. The text is forwarded to the AI provider you have configured.

---

## 4. Microsoft Store Telemetry (When Installed from Store)

When the App is installed from the Microsoft Store, Microsoft may collect standard install/usage telemetry as described in the **Microsoft Privacy Statement** (https://privacy.microsoft.com/privacystatement). This is a Store-level mechanism that is independent of the App's own behavior.

---

## 5. Children's Privacy

The App is not directed to children under the age of 13 and the developer does not knowingly collect any data about minors.

---

## 6. Changes to This Policy

Updates to this policy will be posted to this repository. The "Last updated" date at the top reflects the most recent revision.

---

## 7. Contact

Issues, questions, or data-related requests: please open an issue at
**https://github.com/misstouch-taro/revAIser/issues**

---

# プライバシーポリシー(日本語訳)

*最終更新: 2026-05-16*

revAIser(以下「本アプリ」)は **misstouch-taro** による、ユーザー自身のテキストを第三者の AI サービスを用いて校正・推敲するためのデスクトップアプリです。本ポリシーは本アプリがあなたの情報をどう扱うかを示します。

## 1. 本アプリが収集しないデータ

開発者は以下を一切収集・送信・保管しません。

- 解析(アナリティクス)情報
- テレメトリ情報
- ユーザーの編集テキスト
- 端末ID、MACアドレス、メールアドレス等の識別子

## 2. ローカルに保存されるデータ

本アプリは `%APPDATA%\revAIser\` 配下に以下を保存します。

- **AI プロバイダのAPIキー** — Electron `safeStorage`(Windows では DPAPI)で暗号化
- **アプリ設定** — 選択中AIモデル、言語(ja/en)、ダークモード、カスタムシステムプロンプト
- **ウィンドウ状態** — 直前の位置・サイズ

これらは本アプリの動作でユーザー端末から外には送出されません。アンインストールまたは同梱の reset スクリプトで削除可能です。

## 3. 第三者 AI プロバイダへのテキスト送信

「チェックする」(Ctrl+Enter)を実行すると、左ペインのテキストと**あなたが設定した API キー**が選択中のプロバイダ(Groq / OpenAI / Anthropic)に送信されます。送信後のデータの扱いは各プロバイダのプライバシーポリシーに従います。

**注意**: 機密情報・規制情報(個人情報、営業秘密、医療情報、NDA下のソースコード等)は本アプリに貼り付けないでください。設定中の AI プロバイダに転送されます。

## 4. Microsoft Store 経由のテレメトリ

Microsoft Store 経由でインストールした場合、Microsoft は Microsoft プライバシーステートメント
(https://privacy.microsoft.com/privacystatement) に基づき標準的な利用情報を収集する場合があります。これは Store の仕組みであり、本アプリ自身の挙動とは独立しています。

## 5. 未成年への配慮

本アプリは 13 歳未満の児童を対象としていません。開発者は未成年に関する情報を意図的に収集することはありません。

## 6. 改訂

本ポリシーの更新は本リポジトリに掲示されます。冒頭の「最終更新」日付が最新改訂日です。

## 7. 連絡先

問い合わせ・データ関連リクエストは GitHub Issues までお願いします。
**https://github.com/misstouch-taro/revAIser/issues**
